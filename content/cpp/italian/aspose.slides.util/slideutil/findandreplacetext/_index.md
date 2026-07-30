---
title: FindAndReplaceText()
second_title: Aspose.Slides per C++ Riferimento API
description: Cerca e sostituisce il testo nella presentazione con il formato specificato
type: docs
weight: 40
url: /it/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) metodo

Cerca e sostituisce testo nella presentazione con il formato specificato

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentazione esaminata. |
| withMasters | **bool** | Determina se le diapositive master devono essere esaminate. |
| find | [System::String](../../../system/string/) | Valore stringa da trovare. |
| replace | [System::String](../../../system/string/) | Valore stringa da sostituire. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Formato per la sostituzione della porzione di testo. Se nullo verrà usato il formato del primo carattere della stringa trovata. |
## Osservazioni




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```




## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [String](../../../system/string/)
* Classe [PortionFormat](../../../aspose.slides/portionformat/)
* Classe [SlideUtil](../)
* Spazio dei nomi [Aspose::Slides::Util](../../)
* Libreria [Aspose.Slides](../../../)