---
title: FindAndReplaceText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Busca y reemplaza texto en la presentación con el formato dado
type: docs
weight: 40
url: /es/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) método

Busca y reemplaza texto en la presentación con el formato dado

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentación escaneada. |
| withMasters | **bool** | Determina si las diapositivas maestras deben escanearse. |
| find | [System::String](../../../system/string/) | Valor de cadena a buscar. |
| replace | [System::String](../../../system/string/) | Valor de cadena a reemplazar. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Formato para reemplazar la porción de texto. Si es nulo, se usará el formato del primer carácter de la cadena encontrada. |

## Observaciones




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




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPresentation](../../../aspose.slides/ipresentation/)
* Clase [String](../../../system/string/)
* Clase [PortionFormat](../../../aspose.slides/portionformat/)
* Clase [SlideUtil](../)
* Espacio de nombres [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)