---
title: ReplaceText()
second_title: Aspose.Slides für C++ API Referenz
description: Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.
type: docs
weight: 170
url: /de/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) Methode

Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Die zu ersetzende Zeichenfolge. |
| newText | [System::String](../../../system/string/) | Die Zeichenfolge, die alle Vorkommen von oldText ersetzt. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsuchoptionen [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-Objekt zum Speichern des Ergebnisses der Ersetzungsoperation [IFindResultCallback](../../ifindresultcallback/). |

## Hinweise

Der folgende Beispielcode zeigt, wie ein bestimmter String durch einen anderen bestimmten String ersetzt wird. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Ersetzt alle einzelnen Vorkommen von 'the' durch '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [TextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)