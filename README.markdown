# Phing Yii Template

An XML build file for the [Phing build system](http://www.phing.info/trac/) with tasks and configuration designed for [Yii](http://www.yiiframework.com/) projects.

Based on [phing-drupal-template](http://reload.github.com/phing-drupal-template/).

### Usage
* **build** runs init, clean, verify and analyze
* **verify** runs css-, js- and php-lint and check that there is no debug code laying around
* **analyze** runs phploc, phpmd and phpcpd

```
cd build
phing build #runs init, clean, verify and analyze
```
