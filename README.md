# NestJs Project

Project for polishing the NestJs skills

## Objectives

- Online Video Management Application

* Platform Users

  - Admin
  - Users

* Admin

  - Admin will be able to login into the application by providing a valid email and password(Insert an admin into the database statically)
  - Admin will be able to update his password using email verification(An OTP will be sent to the admin email)
  - Admin will be able to add edit delete list video category(Use pagination in list API)
  - Video should contain
    - Title
    - Description
    - Video (mp4 ony and should be less than 5MB)
    - Tags ( A movie can have multiple tags)

* User

  - Users will be able to create an account and verify their email address
  - User will contain

    - First Name
    - Last Name
    - Email
    - Password (minimun 8 characters long, must have an uppercase, a lowercase, a symbol)

  <br>
  - Users will be able to get an overview of the application ( An API that will return 5 videos of each category)

  - User will be able to get a list of videos

        - Search Options
          - Video Title
          - Category
          - Uploaded Date Range
          - Tags

        - Sort Options(Both Ascending and Descending)

          - Title
          - Uploaded Date

        - API response should have

          * Video Id
          * Video Title
          * Video Description
          * Video Link
          * Tags
          * Uploaded Date
          * Category Details
          * Number of likes

        - The User should get a list of liked videos

        - Users can comment on a video
