---
title: CreatePortion()
second_title: Aspose.Slides for C++ API Reference
description: Creates an empty text portion.
type: docs
weight: 1
url: /cpp/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() method


Creates an empty text portion.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Return Value

[Portion](../../portion/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [IPortionFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPortionFactory::CreatePortion([System::String](../../../system/string/)) method


Creates a text portion from specified string.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Return Value

[Portion](../../portion/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [String](../../../system/string/)
* Class [IPortionFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPortionFactory::CreatePortion([System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>) method


Creates a portion with the using of a specified portion data.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | A portion to use. |

### Return Value

[Portion](../../portion/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [IPortionFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
