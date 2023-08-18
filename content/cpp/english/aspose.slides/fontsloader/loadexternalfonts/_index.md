---
title: LoadExternalFonts()
second_title: Aspose.Slides for C++ API Reference
description: Adds additional folders to seek fonts.
type: docs
weight: 1
url: /aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) method


Adds additional folders to seek fonts.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Directories to read additional fonts. |
## Remarks



The follow examples shows how to load custom fonts from .TTF 
```cpp
// The path to the documents directory.
System::String dataDir = u"C:\\";

// folders to seek fonts
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Load the custom font directory fonts
FontsLoader::LoadExternalFonts(folders);

// Do some work and perform presentation/slides rendering
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Clear Font Cache
FontsLoader::ClearCache();
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontsLoader](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)