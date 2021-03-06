This repo is a calendar displaying library hours from data in the library's [Ex Libris Alma ILS](http://www.exlibrisgroup.com/category/AlmaOverview). Hours information like that in `hours.json` can be retrieved from Alma's [Retrieve Open Hours API](https://developers.exlibrisgroup.com/alma/apis/conf/GET/gwPcGly021p29HpB7XTI4OhSZDjMWegNwHZGZ/4TCMo=/37088dc9-c685-4641-bc7f-60b5ca7cabed). See [Getting Started with Alma APIs](https://developers.exlibrisgroup.com/alma/apis#starting) for more information on creating API-based apps and getting an API key.

The calendar is dependent on [FullCalendar](https://fullcalendar.io) and [Moment.js](https://momentjs.com/) as well as [jQuery](https://jquery.com/).

This software was written for Ithaca College Library and may include some local quirks in terms of how the calendar works, but it should be fairly simple for other Alma libraries to modify this code for their needs.

You can see the calendar at work [here](https://library.ithaca.edu/cal/).