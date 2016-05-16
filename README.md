craft-video-embed-utility
=========================

A Craft CMS plugin providing a Twig filter for embedding video from YouTube and Vimeo URLs

## Usage:

Once installed, a videoEmbed filter will be available to your templates allowing you to embed a video in your page with just the url:

    {{https://www.youtube.com/watch?v=6-HUgzYPm9g|videoEmbed}}

The filter also allows you to provide embed options ([Vimeo example](https://developer.vimeo.com/player/embedding)) as the first argument in the filter:

    {{url|videoEmbed({ byline: 0, autoplay: 1 })}