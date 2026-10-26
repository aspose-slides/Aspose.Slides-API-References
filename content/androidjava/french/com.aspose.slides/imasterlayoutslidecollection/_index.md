---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection de toutes les diapositives de mise en page d’une diapositive maîtresse définie.
type: docs
url: /fr/com.aspose.slides/imasterlayoutslidecollection/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Représente une collection de toutes les diapositives de mise en page d’une diapositive maîtresse définie. Étend l’interface ILayoutSlideCollection avec des méthodes pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page dans le contexte des collections individuelles des diapositives de mise en page du maître.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Ajoute une copie d’une diapositive de mise en page spécifiée à la fin de la collection. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Insère une copie d’une diapositive de mise en page spécifiée à la position indiquée de la collection. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Ajoute une nouvelle diapositive de mise en page à la fin de la collection. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Insère une nouvelle diapositive de mise en page à la position indiquée de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l’élément à l’index spécifié de la collection. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Déplace la diapositive de mise en page de la collection vers la position spécifiée. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Ajoute une copie d’une diapositive de mise en page spécifiée à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à dupliquer. |

1) La nouvelle mise en page sera liée à la diapositive maître parente pour cette collection de mises en page. Il s’agit donc d’un équivalent de copier/coller avec l’option « Utiliser le thème de destination » dans PowerPoint. 2) L’équivalent de cette méthode est la méthode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accessible via la propriété [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Valeur de retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Insère une copie d’une diapositive de mise en page spécifiée à la position indiquée de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à dupliquer. |

La nouvelle mise en page sera liée à la diapositive maître parente pour cette collection de mises en page. Il s’agit donc d’un équivalent de copier/coller avec l’option « Utiliser le thème de destination » dans PowerPoint.

**Valeur de retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive insérée.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Ajoute une nouvelle diapositive de mise en page à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est null, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1\_Title Slide », « 2\_.. », etc.). |

--------------------

1) La mise en page ajoutée pour la valeur SlideLayoutType.Custom de layoutType ne contient aucun espace réservé ni aucune forme. 2) L’équivalent de cette méthode est la méthode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accessible via la propriété [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Valeur de retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Insère une nouvelle diapositive de mise en page à la position indiquée de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est null, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1\_Title Slide », « 2\_.. », etc.). |

La mise en page insérée pour la valeur SlideLayoutType.Custom de layoutType ne contient aucun espace réservé ni aucune forme.

**Valeur de retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive insérée.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l’élément à l’index spécifié de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro de l’élément à supprimer. |

1) Pour éviter le déclenchement de la PptxEditException, vérifiez d’abord la propriété HasDependingSlides de la mise en page. 2) Vous pouvez également utiliser la méthode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pour simplifier le code.
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Déplace la diapositive de mise en page de la collection vers la position spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à déplacer. |