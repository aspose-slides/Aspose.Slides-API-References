---
title: HighlightText()
second_title: Aspose.Slides C++ API Referencia
description: Kiemeli a minta szöveg összes előfordulását a megadott színnel.
type: docs
weight: 495
url: /hu/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) metódus


Kiemeli a minta szöveg összes előfordulását a megadott színnel.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
## Megjegyzések



Az alábbi kódrészlet bemutatja, hogyan lehet kiemelni a szöveget egy PowerPoint-prezentációban. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// az összes különálló 'the' előfordulás kiemelése
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metódus


Kiemeli a minta szöveg összes előfordulását a megadott színnel.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Szövegkeresési beállítások [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásához. |
## Megjegyzések



Az alábbi kódrészlet bemutatja, hogyan lehet kiemelni a szöveget egy PowerPoint-prezentációban. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// az összes különálló 'the' előfordulás kiemelése
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [Presentation](../)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)