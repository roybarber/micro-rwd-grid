# Micro Responsive Grid

A tiny little responsive grid (32 lines of CSS), with a nestable 3 & 4 column setup.

## Browser support

Tested in all browsers, minor stacking bug in IE7 at certain widths, but this is on the roadmap to fix, or send in those pull requests.

## The developer

I am [Roy Barber](http://roybarber.com), I am a 29 year old freelance designer and front end devloper from the UK. I occasionally write some articles [here](http://roybarber.com/blog/)

## Usage

It's easy to work out, but below is an example. When I get time I will improve these docs!

    <div class="container">
        <div class="row">
            <div class="col three-one">3/1</div>
            <div class="col three-one">3/1</div>
            <div class="col three-one tablet-full last">3/1</div>
        </div>

        <div class="row">
			<div class="col four-one">4/1</div>
			<div class="col four-one">4/1</div>
			<div class="col four-one">4/1</div>
			<div class="col four-one last">4/1</div>
		</div>
    </div>

.last is used only to fix a bug in IE7
.tablet-full is used to make the last column (or any) full width when it stacks on tablet's

## License

Copyright 2013 Roy Barber - Licensed under the Apache License, Version 2.0.
