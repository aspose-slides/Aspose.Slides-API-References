---
title: ChartPortionFormat
type: docs
weight: 0
url: /php-java/chartportionformat/
---

# ChartPortionFormat class

 This class contains the chart portion formatting properties used in charts.
 Unlike  IPortionFormatEffectiveData, all properties of this class are writeable.
 
 This class is used to return and manipulate text portion formatting
 properties defined for the particular portion. This means that
 no inheritance is applied when getting values so for the majority of cases
 you will get values meaning "undefined".
 In order to get the effective formatting parameter values including
 inherited you need to use  PortionFormat#getEffective method
 which returns a  IPortionFormatEffectiveData instance.

## Methods

| name | return type | description |
| --- | --- | --- |
| [getVersion](/slides/php-java/chartportionformat/getversion/)() | long |  |
