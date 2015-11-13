http://ruby-gem-downloads-badge.herokuapp.com/ - gem downloads shields
======================================================================

[![Dependency Status](https://gemnasium.com/bogdanRada/ruby-gem-downloads-badge.svg)](https://gemnasium.com/bogdanRada/ruby-gem-downloads-badge) [![Inline docs](http://inch-ci.org/github/bogdanRada/ruby-gem-downloads-badge.svg?branch=master)](http://inch-ci.org/github/bogdanRada/ruby-gem-downloads-badge) [![Code Climate](https://codeclimate.com/github/bogdanRada/ruby-gem-downloads-badge/badges/gpa.svg)](https://codeclimate.com/github/bogdanRada/ruby-gem-downloads-badge) [![Maintenance Status](http://stillmaintained.com/bogdanRada/ruby-gem-downloads-badge.png)](https://github.com/bogdanRada/ruby-gem-downloads-badge)

Clean and simple gem download badge, [courtesy of shields.io](https://github.com/badges/shields), that displays the downloads number of your gem. By default will display the downloads count of the latest version of the gem provided.

##Use

In your README.md, just add an image with the base URL (`http://ruby-gem-downloads-badge.herokuapp.com/`) followed by the gem name and the version, for example :

You will then get a nice and pretty SVG with the downloads count of the gem provided:

```
  ![](http://ruby-gem-downloads-badge.herokuapp.com/rails)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails)

Or you can use any extension you like like this:

```
  ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?extension=png)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?extension=png)

You can also specify the version of the gem, for example:

```
  ![](http://ruby-gem-downloads-badge.herokuapp.com/rails/4.1.0)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails/4.1.0)

You can also specify to display the total downloads count like this:

```
  ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?type=total)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?type=total)

You can also specify to display the total downloads count for a version like this:

```
  ![](http://ruby-gem-downloads-badge.herokuapp.com/rails/4.1.0?type=total)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails/4.1.0?type=total)

If you want a flat image, you can add `&style=flat` at the end of the url.

```
![](http://ruby-gem-downloads-badge.herokuapp.com/rails?style=flat)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?style=flat)

If you want a plastic image, you can add `&style=plastic` at the end of the url.

```
![](http://ruby-gem-downloads-badge.herokuapp.com/rails?style=plastic)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?style=plastic)

If you want a flat-square image, you can add `&style=flat-square` at the end of the url.

```
![](http://ruby-gem-downloads-badge.herokuapp.com/rails?style=flat-square)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?style=flat-square)

If you want the downloads count to use metrics,, you can add `&metric=true` at the end of the url.

```
![](http://ruby-gem-downloads-badge.herokuapp.com/rails?metric=true)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?metric=true)

That's it!

###Further Customization

If you want to change the color of your badge, just append `&color=COLOR_NAME` to the image URL. By default, the badge is blue.

Available colors are (gem is rails):

|    Color    |                                         Badge                                         |
|:-----------:|:-------------------------------------------------------------------------------------:|
| brightgreen | ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=brightgreen&style=flat) |
|    green    |    ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=green&style=flat)    |
| yellowgreen | ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=yellowgreen&style=flat) |
|   yellow    |   ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=yellow&style=flat)    |
|   orange    |   ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=orange&style=flat)    |
|     red     |     ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=red&style=flat)     |
|  lightgray  |  ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=lightgray&style=flat)  |
|    blue     |    ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=blue&style=flat)     |
|   ff69b4    |   ![](http://ruby-gem-downloads-badge.herokuapp.com/rails?color=ff69b4&style=flat)    |

If you specify a version that is not valid like this, you will see a invalid image:

```
![](http://ruby-gem-downloads-badge.herokuapp.com/rails/4.1.dsad)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails/4.1.dsad)

If you want something else written on the badge you can use:

```
![](http://ruby-gem-downloads-badge.herokuapp.com/rails?status=something-else)
```

![](http://ruby-gem-downloads-badge.herokuapp.com/rails?status=something-else)

---

**This repository was created by bogdanRada - but is completely built off of [shields.io](http://github.com/badges/shields) - go check them out! Having a problem? [Open an issue.](http://github.com/bogdanRada/gem-downloads-badge/issues)**
