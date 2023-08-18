---
title: CreatePortion()
second_title: Aspose.Slides for C++ API Reference
description: Creates an empty text portion.
type: docs
weight: 1
url: /aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() method


Creates an empty text portion.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### Return Value

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) method


Creates a text portion from specified string.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Return Value

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) method


Creates a portion with the using of a specified portion data.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
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
* Class [PortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)