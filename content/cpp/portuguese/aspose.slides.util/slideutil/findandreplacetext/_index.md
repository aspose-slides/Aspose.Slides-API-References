---
title: FindAndReplaceText()
second_title: Referência da API Aspose.Slides para C++
description: Encontra e substitui texto na apresentação com o formato fornecido
type: docs
weight: 40
url: /pt/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) método


Encontra e substitui texto na apresentação com o formato fornecido

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Apresentação analisada. |
| withMasters | **bool** | Determina se os slides mestre devem ser analisados. |
| find | [System::String](../../../system/string/) | Valor de string a ser encontrado. |
| replace | [System::String](../../../system/string/) | Valor de string a ser substituído. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Formato para substituir a porção de texto. Se nulo, será usado o formato do primeiro caractere da cadeia encontrada |
## Observações




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




## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [String](../../../system/string/)
* Classe [PortionFormat](../../../aspose.slides/portionformat/)
* Classe [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)