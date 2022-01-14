# ✨ Pave QA Test

Hello! 👋

Welcome to the Pave QA Test! This is a copy of [our Pave website](https://wwwpaveapp.com/) but with a bunch of issues deliberately introduced — for example:

- Typos
- Broken or incorrect links
- Incorrect text
- Missing or broken scripts

Your task is to find and locate as many of these bugs as possible and write good bug tickets for each of them.

You can view this page easily by going to https://teampave.github.io/qa-test/.

## Bug Tickets

Our bug tickets follow a standard format — here is an example bug report

> Title: Users entering text in the Google search box are not getting any results returned

> Users who type some text into the search box on the Google home page are always seeing 0 results returned.
>
> _Steps To Reproduce:_
>
> 1. Go to https://google.com
> 2. Enter "google" in the search box
> 3. Press enter
>
> _Expected Behaviour:_
>
> There should be > 0 results, and the first result should be https://google.com.
>
> _Actual Behaviour:_
>
> There are 0 results

Try to make your bugs follow this standard format as much as possible.

## License

This test is licensed [under an MIT license](LICENSE.md).
