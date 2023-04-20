---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API Reference
description: Reads an existing presentation from array
type: docs
weight: 27
url: /cpp/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) method


Reads an existing presentation from array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array to read |

### Return Value

Read presentation

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) method


Reads an existing presentation from array with additional load options

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array to read |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Return Value

Read presentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) method


Reads an existing presentation from stream

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream to read |

### Return Value

Read presentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) method


Reads an existing presentation from stream with additional load options

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream to read |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Return Value

Read presentation

## IPresentationFactory::ReadPresentation(System::String) method


Reads an existing presentation from file

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File name |

### Return Value

Read presentation

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) method


Reads an existing presentation from stream with additional load options

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File name |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Return Value

Read presentation

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [IPresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)