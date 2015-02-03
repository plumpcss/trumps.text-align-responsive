# Text-align-responsive

The plumpcss `text-align-responsive` module is an extension of the default [`text-align`
module](https://github.com/plumpcss/trumps.text-align).

Install using Bower:

    $ bower install --save plumpcss-text-align-responsive

`text-align-responsive` will inherit the same settings used for `text-align` (i.e.
symbol format (e.g. .ta>) or an abbreviated format (e.g. .tar)).

`text-align-responsive` loops through the breakpoints defined in
`settings.responsive` to generate prefixed breakpoint-based classes. If you are
using inuitcss’ default breakpoints, you will be given classes like
`lap-and-up-f>`, or `desk-fr`, etc.
