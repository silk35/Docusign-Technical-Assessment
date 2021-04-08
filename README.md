# Docusign-Technical-Assessment

It took me a while to get Postman setup with the Docusign APIs. It has been over three years since I last used it so I had to learn it again.

Question 1 was pretty straight forward.

Question 2 did not look to have any errors. Just to confirm, I copied the json and used jsonlint to make sure the formatting is correct. I then pasted it into Postman and it was able to send successfully. I'm not sure if this was a mistake or not.

Question 3 I tried to send but I got this error:

{
    "errorCode": "USER_DOES_NOT_BELONG_TO_SPECIFIED_ACCOUNT",
    "message": "The specified User is not a member of the specified Account. User is not a member of the template's account."
}

I'm assuming that this is because my user account is not part of the template account and as such I can't use these templates. So I can't confirm whether the json is correct.
