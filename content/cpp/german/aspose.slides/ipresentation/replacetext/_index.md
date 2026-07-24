---
title: ReplaceText()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.
type: docs
weight: 482
url: /de/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) Methode


Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Die zu ersetzende Zeichenkette. |
| newText | [System::String](../../../system/string/) | Die Zeichenkette, die alle Vorkommen von oldText ersetzt. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsuche-Optionen [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |
## Anmerkungen



Der folgende Beispielcode zeigt, wie man eine angegebene Zeichenkette durch eine andere angegebene Zeichenkette ersetzt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Ersetzt alle einzelnen 'the'-Vorkommen durch '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [IPresentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)