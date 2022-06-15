---
title: BiLevel
type: docs
weight: 0
url: /php-java/bilevel/
---

# BiLevel class

 Represents a Bi-Level (black/white) effect.
 Input colors whose luminance is less than the specified threshold value are changed to black.
 Input colors whose luminance are greater than or equal the specified value are set to white.
 The alpha effect values are unaffected by this effect.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [equals](/slides/php-java/bilevel/equals/)(Object) | boolean | Determines whether the specified BiLevel is equal to the current BiLevel. |
| [getEffective](/slides/php-java/bilevel/geteffective/)() | IBiLevelEffectiveData | Gets effective Bi-Level effect data with the inheritance applied. |
| [hashCode](/slides/php-java/bilevel/hashcode/)() | int | Serves as a hash function for a particular type. |
