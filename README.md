# Dev_Planning_About_Gherkin

# GHERKIN

- Domain specific language which helps you to describe business behavior without the need to go into detail of implementation

### Gherkin Syntax

- Feature: Tile of the Scenario
- Given: [Preconditions or Initial Context]
- When: [Event or Trigger]
- Then: [Expected output]

### Important Terms used in Gherkin

- Feature
- Background
- Scenario
- Given
- When
- Then
- And
- But

### Example 1)

- Feature: Login functionality of social networking site Facebook.
- Given: I am a facebook user
- When: I enter username as username
- And I enter the password as the password
- Then I should be redirected to the home page of facebook

### Example 2)

- Feature: User Authentication Background:
- Given the user is already registered to the website Scenario:
- Given the user is on the login page
- When the user inputs the correct email address
- And the user inputs the correct password
- And the user clicks the Login button
- Then the user should be authenticated
- And the user should be redirected to their dashboard
- And the user should be presented with a success message
