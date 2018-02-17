# trendingVideos

Create "Youtube Videos" content type to store youtube video information mainly 2 things: Video itself and Tag.
Create custom form to import videos for a specific keyword.
Administrators/Managers provide keyword as input
That Keyword should be added as taxonomy term to the Vocabulary. If term already exists Show message "This keyword
already exists, try new keywords" else try importing corresponding videos using Youtube Data API (at least 20).
Create nodes corresponding to the results.
