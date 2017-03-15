Using Markdown
==============

Markdown is the text formatting that the Unlocked Grammar projects use. The project sites include a built-in Markdown editor and previewer so that in-depth knowledge of the format is typically not necessary. However, there are a few exceptions when knowledge of Markdown format is helpful or necessary.

Line Breaks
-----------

If you want text to show up on separate lines then you need 2 line breaks between the lines.  For example:

``this will be on
the same line``

Shows up as

this will be on
the same line

But the following will show up on separate lines:

``this will be on``

``separate lines``

Like this:

this will be on

separate lines


Tables
------

Since Markdown does not natively support all of the features required, such as row and column spans, tables required for the Unlocked Grammar declension and other paradigms/charts need to be created in HTML format. If you are not familiar with HTML, the easiest way to generate the HTML for these tables is to copy and paste the text into an `HTML table generator <http://www.tablesgenerator.com/html_tables#>`_. 

.. note:: Charts are needed for many paradigms and declensions. These should be taken from public domain grammars to avoid copyright issues. For Greek, Nunn and Moulton are two public domain grammars that can be used. To save time, copy paradigms/charts from an electronic source rather than hand typing them. Some are probably on the Internet free (e.g., at archive.org) perhaps even in HTML format. However, some of those will need to be modified since older grammars tend to list 'thou' and 'ye' to differentiate 2nd person sg. & pl. and those should be 'you' or 'you (sg.)' and 'you (pl.). Also, the terminology and abbreviations need to be consistent in all charts so that means some of the public domain charts will need to be modified.

To use the `HTML table generator <http://www.tablesgenerator.com/html_tables#>`_ in Markdown files:

1. Copy and paste your text into the formatted table view.

.. note:: Each paradigm table or chart should be complete with row and column headers, accents, vowels, and the English translation/equivalent for each cell.

2. Check the box for "Do not generate CSS".
3. Click the **Generate** button.
4. Copy the resulting HTML code.
5. Click the Edit button for the appropriate Markdown file where the HTML table code belongs.
6. Paste the HTML code into the Markdown file.
7. Preview the file to make sure formatting is correct.
8. If the chart or paradigm is complete, click the **Commit Changes** button to save the file changes to your fork.

