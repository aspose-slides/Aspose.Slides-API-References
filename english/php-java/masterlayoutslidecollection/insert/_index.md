---
title: insert
type: docs
weight: 30
url: /php-java/masterlayoutslidecollection/insert/
---

# insert(int, byte, java.lang.String) method

 Inserts a new layout slide to specified position of the collection.
 

##  Parameters

| name | description |
| --- | --- |
| index | Index of new slide. |
| layoutType | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1_Title Slide", "2_..", etc.). Inserted layout for value SlideLayoutType.Custom of layoutType contains no placeholders and no shapes. |

##  Returns
Inserted slide.

##  Exception
com.aspose.ms.System.ArgumentException Thrown if layout name value layoutName is already in use in this collection of the layouts.

