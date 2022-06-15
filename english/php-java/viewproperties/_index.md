---
title: ViewProperties
type: docs
weight: 0
url: /php-java/viewproperties/
---

# ViewProperties class

 Presentation wide view properties.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getLastView](/php-java/viewproperties/getlastview/)() | int | Specifies the view mode that was used when the presentation document was last saved. Read/write ViewType. |
| [getNormalViewProperties](/php-java/viewproperties/getnormalviewproperties/)() | INormalViewProperties | Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region. Read-only INormalViewProperties. |
| [getNotesViewProperties](/php-java/viewproperties/getnotesviewproperties/)() | ICommonSlideViewProperties | Specifies common view properties associated with the notes view mode. Read-only ICommonSlideViewProperties. |
| [getShowComments](/php-java/viewproperties/getshowcomments/)() | byte | Specifies whether the slide comments should be shown. Read/write NullableBool. |
| [getSlideViewProperties](/php-java/viewproperties/getslideviewproperties/)() | ICommonSlideViewProperties | Specifies common view properties associated with the slide view mode. Read-only ICommonSlideViewProperties. |
| [setLastView](/php-java/viewproperties/setlastview/)(int) | void | Specifies the view mode that was used when the presentation document was last saved. Read/write ViewType. |
| [setShowComments](/php-java/viewproperties/setshowcomments/)(byte) | void | Specifies whether the slide comments should be shown. Read/write NullableBool. |
