---
title: Hyperlink()
second_title: Aspose.Slides for C++ API Reference
description: Creates an instance of a hyperlink.
type: docs
weight: 326
url: /aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) constructor


Creates an instance of a hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) constructor


Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Target slide. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) constructor


Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Source hyperlink |
| targetFrame | [System::String](../../../system/string/) | Target frame |
| tooltip | [System::String](../../../system/string/) | Tooltip text |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Hyperlink](../)
* Class [ISlide](../../islide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)