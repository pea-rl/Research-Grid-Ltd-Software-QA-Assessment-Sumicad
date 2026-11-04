# TASK 1
Your first task is to write down all possible test cases and at least 2 possible edge cases against
the User Story below.
● Inclusive is a web based application, designed to eliminate the most common
bottlenecks in engagement to ensure participation is inclusive and scalable.
● The application is accessible via different devices, that includes (but not limited to)
Desktop, Laptop, Tablet and Mobile.
● The below screenshot is attached to help you visualize the login procedure of the
application. Users should be able to login to the system using the correct credentials.

## TC No.: 001
**Test Scenario:** Successful sign in

**Description:** Verify that a user with a valid, existing account can successfully authenticate using the correct email address and password and access the application.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid existing account

**Test Data:** valid email and password

**Steps:**
1. Go to R.grid Inclusive Login page
2. Input valid email address
3. Input valid password
4. Click/tap Sign In button

**Expected Result:** User should be able to sign in and redirect to the home page.

---

## TC No.: 002
**Test Scenario:** Unsuccessful sign in - Invalid Password

**Description:** Verify that the system prevents a user from signing in when an incorrect password is entered for an existing account and displays an appropriate error message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid existing account

**Test Data:** valid email and invalid password

**Steps:**
1. Go to R.grid Inclusive Login page
2. Input valid email address
3. Input invalid password
4. Click/tap Sign In button

**Expected Result:** Error message should be displayed prompting the user that password was incorrect.

---

## TC No.: 003
**Test Scenario:** Unsuccessful sign in - Invalid email

**Description:** Verify that the system prevents a user from signing in when an invalid or unregistered email address is entered and displays an appropriate error message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid existing account

**Test Data:** invalid email and valid password

**Steps:**
1. Go to R.grid Inclusive Login page
2. Input invalid email address
3. Input valid password
4. Click/tap Sign In button

**Expected Result:** Error message should be displayed prompting the user that email was incorrect.

---

## TC No.: 004
**Test Scenario:** Unsuccessful sign in - invalid credentials

**Description:** Verify that the system prevents a user from signing in when both the email address and password do not match an existing account and displays an appropriate error message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:**

**Test Data:** unregistered account

**Steps:**
1. Go to R.grid Inclusive Login page
2. Input invalid email and password
3. Click/tap Sign In button

**Expected Result:** Error message should be displayed prompting the user that email and password was incorrect.

---

## TC No.: 005
**Test Scenario:** Reset password and successful sign in

**Description:** Verify that the user can successfully reset their password using the password recovery process and sign in with the newly updated password.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid credentials

**Test Data:** valid email and address and valid new password

**Steps:**
1. Go to R.grid Inclusive Login page
2. Click/tap Forgot Password
3. Input valid email address
4. Click/tap Reset password button
5. Check email then click the link provided for password reset
6. Input valid new password
7. Click/tap Reset password
8. Go to R.grid Inclusive Login page
9. Input valid email address
10. Input the valid new address
11. Click/tap Sign In button

**Expected Result:** User should be redirected to the home page.

---

## TC No.: 006
**Test Scenario:** Reset password - password requirement error

**Description:** Verify that the system prevents a user from resetting their password when the new password does not meet the specified password requirements and displays an appropriate validation message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid credentials

**Test Data:** valid email and address and invalid new password

**Steps:**
1. Go to R.grid Inclusive Login page
2. Click/tap Forgot Password
3. Input valid email address
4. Click/tap Reset password button
5. Check email then click the link provided for password reset
6. Input invalid new password

**Expected Result:** Error message should be displayed prompting the user that the password does not fulfill the password requirements.

---

## TC No.: 007
**Test Scenario:** Reset password - invalid email

**Description:** Verify that the system validates the email address entered in the Forgot Password form and prevents a password reset request when the email address has an invalid format, displaying an appropriate validation message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid credentials

**Test Data:** invalid email address

**Steps:**
1. Go to R.grid Inclusive Login page
2. Click/tap Forgot Password
3. Input invalid email address
4. Click/tap Reset password button

**Expected Result:** Error message should be displayed prompting the user that the email address input is in incorrect format.

---

## TC No.: 008
**Test Scenario:** Reset password - unregistered email address

**Description:** Verify that the system does not initiate a password reset request or send a password reset email when an email address that is not associated with an existing account is submitted.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** active email address

**Test Data:** unregistered email address

**Steps:**
1. Go to R.grid Inclusive Login page
2. Click/tap Forgot Password
3. Input unregistered email address
4. Click/tap Reset password button

**Expected Result:** User should not be able to receive any password reset email.

---

## TC No.: 009
**Test Scenario:** Successful sign up

**Description:** Verify that a new user can successfully create an account by providing valid registration details, accepting the required agreements and cookie policy, and submitting the sign-up form. The user should be redirected to the home page after successful registration.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** active email address and not registered to the system

**Test Data:** active email address

**Steps:**
1. Go to R.grid Inclusive Sign Up page
2. Input valid fullname
3. Input active email address
4. Input valid password
5. Input correct password for confirmation
6. Check the agreement and cookie policy
7. Click/tap Sign Up button

**Expected Result:** User should be able to successfully sign up and is redirected to the home page.

---

## TC No.: 010
**Test Scenario:** Sign up – existing email

**Description:** Verify that the system prevents a user from registering a new account using an email address that is already associated with an existing account and displays an appropriate error message indicating that the email address is already registered.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** existing valid credentials

**Test Data:** valid email address

**Steps:**
1. Go to R.grid Inclusive Sign Up page
2. Input valid fullname
3. Input existing email address

**Expected Result:** Error message should be displayed prompting the user that the email address was taken and existing.

---

## TC No.: 011
**Test Scenario:** Sign up - password requirements not met

**Description:** Verify that the system validates the password entered during registration and prevents account creation when the password does not meet the specified password requirements, displaying an appropriate validation message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** active email address and not registered to the system

**Test Data:** active email address

**Steps:**
1. Go to R.grid Inclusive Sign Up page
2. Input valid fullname
3. Input active email address
4. Input invalid password

**Expected Result:** Error message should be displayed prompting the user that the password does not fulfill the password requirements.

---

## TC No.: 012
**Test Scenario:** Sign up - password reconfirmation

**Description:** Verify that the system checks whether the password and password confirmation fields contain matching values and prevents account creation when the passwords do not match, displaying an appropriate validation message.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** active email address and not registered to the system

**Test Data:** active email address

**Steps:**
1. Go to R.grid Inclusive Sign Up page
2. Input valid fullname
3. Input active email address
4. Input valid password
5. Input invalid password reconfirmation

**Expected Result:** Error message should be displayed indicating that the password and password confirmation do not match, and the user should not be able to proceed with registration.

---

## TC No.: 013
**Test Scenario:** Sign up - unchecked agreement policy and cookie policy

**Description:** Verify that the system prevents a user from submitting the sign-up form when the required agreement and cookie policy checkboxes are left unchecked, ensuring that the user must acknowledge the required policies before proceeding with registration.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** active email address and not registered to the system

**Test Data:** active email address

**Steps:**
1. Go to R.grid Inclusive Sign Up page
2. Input valid fullname
3. Input active email address
4. Input valid password
5. Input correct password for confirmation
6. Leave the agreement and cookie policy unchecked

**Expected Result:** Sign Up button should remain disabled or prevent form submission until the required agreement and cookie policy checkboxes are checked. An appropriate prompt should inform the user that these requirements must be acknowledged.

---

## TC No.: 014
**Test Scenario:** Browser compatibility

**Description:** Verify that the R.grid Inclusive application functions consistently across supported web browsers and that its login and sign-up pages display and operate correctly without browser-specific issues.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** supported browsers installed

**Test Data:** supported browsers

**Steps:**
1. Go to R.grid Inclusive login page using the first supported browser.
2. Inspect the page layout and verify that all elements are displayed correctly.
3. Navigate to the Sign Up page.
4. Inspect the page layout and verify that all elements are displayed correctly.
5. Repeat steps 1–5 using each supported browser.

**Expected Result:** The application should display and function consistently across all supported browsers. Login and sign-up elements should be properly rendered, accessible, and functional without browser-specific errors or layout issues.

---

## TC No.: 015
**Test Scenario:** Keyboard submission trigger

**Description:** Verify that users can submit the login form using the keyboard's Enter key after entering valid login credentials, without needing to click or tap the Sign In button.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:** valid existing account

**Test Data:** valid credentials

**Steps:**
1. Go to the R.grid Inclusive login page.
2. Input a valid email address.
3. Input a valid password.
4. Press the Enter key while focused on the password field.

**Expected Result:** The system should submit the login form and successfully authenticate the user, redirecting them to the home page.

---

## TC No.: 016
**Test Scenario:** UI responsiveness

**Description:** Verify that the R.grid Inclusive application adapts its user interface to different screen sizes and orientations across desktop, laptop, tablet, and mobile devices, ensuring that all elements remain properly displayed and accessible.

**Device:** ALL (Desktop, Laptop, Tablet, Mobile)

**Preconditions:**

**Test Data:**

**Steps:**
1. Go to R.grid Inclusive login
2. Inspect the layout and positioning of all visible elements.
3. Repeat the inspection using different screen resolutions.
4. Change the orientation of tablet and mobile devices between portrait and landscape.
5. Navigate to the Sign Up page and repeat the checks.
6. Observe whether any elements overlap, become clipped, or require unintended horizontal scrolling.

**Expected Result:** The application should automatically adjust its layout according to the device's screen size and orientation. All text, input fields, buttons, and other interface elements should remain visible, properly aligned, and accessible without unintended overlapping, clipping, or horizontal scrolling.

---

## TC No.: 017
**Test Scenario:** Device orientation

**Description:** Verify that the login page layout adjusts correctly when the device orientation changes between portrait and landscape while preserving any credentials already entered by the user.

**Device:** Tablet, Mobile

**Preconditions:**

**Test Data:**

**Steps:**
1. Go to the R.grid Inclusive login page on a tablet or mobile device.
2. Enter an email address and password.
3. Rotate the device from portrait to landscape orientation.
4. Observe the login page layout and entered credentials.
5. Rotate the device back to portrait orientation.
6. Observe the layout and entered credentials again.

**Expected Result:** The layout should adjust automatically without requiring a page reload. All login elements should remain visible and accessible, and entered credentials should not be lost.

---

## TC No.: 018
**Test Scenario:** Textbox and button accessibility

**Description:** Verify that interactive elements on the login page, including input fields and buttons, are accessible and usable through touch interactions on tablet and mobile devices.

**Device:** Tablet, Mobile

**Preconditions:**

**Test Data:** valid email address and password

**Steps:**
1. Go to R.grid Inclusive login page.
2. Tap the email input field.
3. Input an email address.
4. Tap the password input field.
5. Input a password.
6. Tap the Sign In button.
7. Observe whether the interactive elements respond correctly to touch.

**Expected Result:** All interactive elements should respond correctly to touch interactions. Input fields and buttons should have adequate touch target sizes and spacing to prevent accidental selections or difficulty interacting with them.

---

## TC No.: 019
**Test Scenario:** Form visibility - virtual keyboard visible

**Description:** Verify that the login form remains visible and accessible when the virtual keyboard is displayed on tablet and mobile devices.

**Device:** Tablet, Mobile

**Preconditions:**

**Test Data:** valid email address and password

**Steps:**
1. Go to R.grid Inclusive login page.
2. Tap the email input field to display the virtual keyboard.
3. Observe whether the active input field remains visible.
4. Enter an email address.
5. Tap the password input field.
6. Observe whether the active input field and required login controls remain accessible while the virtual keyboard is displayed.
7. Dismiss the virtual keyboard and inspect the login page.

**Expected Result:** The virtual keyboard should not obscure the active input field or prevent access to required login controls. The user should be able to enter credentials and interact with the login form without difficulty.