---
title: FindAndReplaceText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche et remplace le texte dans la présentation avec le format donné
type: docs
weight: 40
url: /fr/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) méthode

Recherche et remplace le texte dans la présentation avec le format donné

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Présentation analysée. |
| withMasters | **bool** | Détermine si les diapositives maîtres doivent être analysées. |
| find | [System::String](../../../system/string/) | Valeur de chaîne à rechercher. |
| replace | [System::String](../../../system/string/) | Valeur de chaîne à remplacer. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Format pour remplacer la portion de texte. Si null, le format du premier caractère de la chaîne trouvée sera utilisé. |

## Remarques




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



## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [String](../../../system/string/)
* Classe [PortionFormat](../../../aspose.slides/portionformat/)
* Classe [SlideUtil](../)
* Espace de noms [Aspose::Slides::Util](../../)
* Bibliothèque [Aspose.Slides](../../../)