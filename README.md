# twitter-timeline-embed
Twitter has become a standard social media channel for most online brands and Twitter feeds have become increasingly popular on websites. This tutorial aims to teach you how to add some styles to your website's Twitter feed.  In order to use this tutorial you will need to navigate to your Twitter account and pull the code for your embeddable widget. Once you have done that we will use HTML and CSS to style the widget to match our own branding. We will explain every change along the way, beginning with Twitter's original embed widget code.

## Tutorial

For detailed instructions, visit Solodev's [Styling your Website's Twitter Feed](https://www.solodev.com/blog/web-design/styling-your-websites-twitter-feed.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/t8vLor7w/).

## HTML

The twitter timeline embed contains the following basic HTML markup.

```
<div class="row">
   <div class="col-md-4"></div>
   <div class="container">
      <div class="col-md-4">
         <div class="panel panel-danger">
            <div class="panel-heading">
               <h3 class="panel-title"><i class="fa fa-twitter-square" aria-hidden="true"></i>
                  Solodev Live
               </h3>
            </div>
            <div class="panel-body">
               <a class="twitter-timeline" data-width="100%" href="https://twitter.com/solodev">Tweets by solodev</a> 
            </div>
         </div>
      </div>
   </div>
   <div class="col-md-4">
   </div>
</div>
<script async src="//platform.twitter.com/widgets.js
```

## CSS

All necessary CSS is in twitter-feed.css

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
```

## Notes

Although this tutorial contains all of the code you will need to style your website's Twitter feed, downloading this repo locally will only show those style changes and not display your Twitter Timeline because it is being pulled by an API.
