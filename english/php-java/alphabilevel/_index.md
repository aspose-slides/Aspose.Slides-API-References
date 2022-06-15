---
title: AlphaBiLevel
type: docs
weight: 0
url: /php-java/alphabilevel/
---

# AlphaBiLevel class

 Represents an Alpha Bi-Level effect.
 Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and
 alpha values greater than or equal to the threshold are changed to 100% (fully opaque).
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [equals](/php-java/alphabilevel/equals/)(Object) | boolean | Determines whether the specified AlphaBiLevel is equal to the current AlphaBiLevel. |
| [getEffective](/php-java/alphabilevel/geteffective/)() | IAlphaBiLevelEffectiveData | Gets effective Alpha Bi-Level effect data with the inheritance applied. |
| [getThreshold](/php-java/alphabilevel/getthreshold/)() | float | Returns effect threshold. Read/write float. |
| [hashCode](/php-java/alphabilevel/hashcode/)() | int | Serves as a hash function for a particular type. |
| [setThreshold](/php-java/alphabilevel/setthreshold/)(float) | void | Returns effect threshold. Read/write float. |
