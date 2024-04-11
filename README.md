I wanted to add functionality into Sudonix so that it

a) Adds a new DIV in the form of a panel/card after the last post if the topic is "solved"
b) Adds a link that will take you straight to the solution
c) Scrolls to that particular DIV containing the solution using page scrolling with an offset

Widget code below:

https://github.com/phenomlab/nodebb-q-a-extension/blob/main/widget.html

#### How to use

1. Open `/admin/extend/widgets`
2. Drag and drop a HTML widget into the `topic.tpl` template, positioned in the Topic Footer
3.  Paste the code from Github into the HTML pane
4. Save the changes

Add this into your custom CSS `/admin/appearance/customise#custom-css`. Note that this is a "starting point" that uses `var` and so you will need to adjust to fir your own site.

https://github.com/phenomlab/nodebb-q-a-extension/blob/main/style.css

From now, any topics which are enabled for Q&A and set to a question will include this new code
