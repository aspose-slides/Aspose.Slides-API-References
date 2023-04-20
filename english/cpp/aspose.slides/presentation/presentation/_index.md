---
title: Presentation()
second_title: Aspose.Slides for C++ API Reference
description: This constructor creates new presentation from scratch. Created presentation has one empty slide.
type: docs
weight: 404
url: /cpp/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() constructor


This constructor creates new presentation from scratch. Created presentation has one empty slide.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


This constructor creates new presentation from scratch. Created presentation has one empty slide.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) constructor


This constructor is the primary mechanism for reading an existing [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream. |
## Remarks




```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


This constructor is the primary mechanism for reading an existing [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## Presentation::Presentation(System::String) constructor


This constructor gets a source file path from which the contents of the [Presentation](../) are read.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file. |
## Remarks




```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) constructor


This constructor gets a source file path from which the contents of the [Presentation](../) are read.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)