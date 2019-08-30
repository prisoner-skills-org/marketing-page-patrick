# marketing-page-patrick

Author: Patrick Stevenson

This repo contains the markup and styling for the Prisoner Skills marketing, about, and contact pages. The styling is done using less, which has been compiled to CSS.

The marketing page, index.html, contains basic marketing copy for potential customers, namely, employers and prison administrators.

The about page, about.html, contains a list of team members who worked on the Prisoner Skills project, organized by role, along with a short bio, picture, and link to his or her GitHub page.

The contact page, contact.html, contains a contact form, which sends an email to my address.

The styling is broken down into variables, global, navigation, page-content, and footer. These less files are imported by index.less, which is compiled to index.css by less-watch-compiler on the development machine. A Meyers reset is also used.

The repo uses three media queries, defined by the variables @phone, @narrow, and @realNarrow, to provide responsiveness to the pages.

A font from Google Fonts, "Roboto," is used throughout the pages.

A logo, designed by a front-end developer on the Prisoner Skills project, is used in the header of the pages.
