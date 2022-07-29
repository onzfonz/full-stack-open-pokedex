## Answer to 11.1

If I were to pick my own project for a CI/CD setup, I would go with C# as the language to use.
For Linting, I think I would go with Stylecop to help find particular issues, since it could be run almost in a lint style with eslint
For testing, I would go with NUnit
For building, I would use a unity assembly definition

For other alternatives, I would use gitlab, circle ci and travis with a combo of bitbucket

I think the setup would be better self-hosted because the time that it would take to build in particular unity projects often takes a really long time and is quite cumbersome, and the artifacts that are generated often take up a lot of space, not to mention the use of the GPU which you mentioned would be something that self-hosting would not necessarily do as well with.  I think the information that I would really need in order to make this information is more about the types of tests that we would run and if there are any optimizers that are out there that would be better suited to running, building and deploying the game in a shorter amount of time.
