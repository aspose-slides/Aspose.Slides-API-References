---
title: IGlobalLayoutSlideCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de toutes les diapositives de mise en page d'une présentation.
type: docs
url: /fr/com.aspose.slides/igloballayoutslidecollection/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Représente une collection de toutes les diapositives de mise en page d'une présentation. Étend l'interface ILayoutSlideCollection avec des méthodes d'ajout/clonage de diapositives de mise en page dans le contexte de l'union des collections individuelles de diapositives maîtres de mise en page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Ajoute une nouvelle diapositive de mise en page à la présentation. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à cloner.

--------------------

Lors du clonage d'une mise en page entre différentes présentations, le maître de la mise en page peut également être cloné afin de conserver le formatage d'origine. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d'éviter la création de plusieurs clones de la même diapositive maître. Le clonage manuel des diapositives maîtres ne sera ni empêché ni enregistré. |

**Valeur renvoyée :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à cloner. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive maître pour une nouvelle mise en page.

--------------------

La nouvelle mise en page sera liée au maître défini dans la présentation de destination. Il s'agit donc d'une analogie de copier/coller avec l'option « Utiliser le thème de destination » dans PowerPoint. |

**Valeur renvoyée :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Ajoute une nouvelle diapositive de mise en page à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive maître pour une nouvelle mise en page. |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est nul, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1\_Title Slide », « 2\_.. », etc.). |

--------------------

1) Mise en page ajoutée pour la valeur SlideLayoutType.Custom de layoutType ne contenant aucun espace réservé ni aucune forme. 2) L'analogue de cette méthode est la méthode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessible via la propriété ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Valeur renvoyée :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.