# jpInView
Simple checker for the question "is an element in view?"

Add the 'inView' class to your elements, this script will
loop through them to see if they are in the widow enough
to be considered "in view". If they are they get the class
"is-inView" and "touched-inView". The class "is-inView" is
removed when an element is no longer in view, but the
"touched-inView" class will remain.

You can modify the percentage of the window you want to
consider "in view". This is the threshold where an element
must scroll into this area before it is in view.

For example, if the window is 900px in height, then 80% of
the screen is 720px. So a section would have to be
within that 720px to get the 'is-inView' class applied to
it.
