---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente une collection de toutes les diapositives de mise en page dans la présentation.
type: docs
url: /fr/com.aspose.slides/igloballayoutslidecollection/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Représente une collection de toutes les diapositives de mise en page d’une présentation. Étend l’interface ILayoutSlideCollection avec des méthodes pour ajouter/dupliquer des diapositives de mise en page dans le contexte d’union des collections individuelles de diapositives de mise en page maîtres.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Adds a new layout slide to the presentation. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à dupliquer. |

--------------------

Lors de la duplication d’une mise en page entre différentes présentations, le maître de la mise en page peut également être dupliqué afin de conserver le formatage source. Un registre interne est utilisé pour suivre les maîtres dupliqués automatiquement afin d’éviter la création de plusieurs copies du même maître de diapositive. La duplication manuelle des maîtres de diapositives n’est ni empêchée ni enregistrée.

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à dupliquer. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive maître pour la nouvelle mise en page. |

--------------------

La nouvelle mise en page sera liée au maître défini dans la présentation de destination. Il s’agit donc de l’équivalent d’un copier-coller avec l’option « Utiliser le thème de destination » dans PowerPoint.

**Retour :**
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
| layoutType | byte | Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Les autres types de mise en page ne sont pas supportés pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nom de la nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre est nul, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide », « 1_Title Slide », « 2_… », etc.). |

--------------------

1) Une mise en page ajoutée pour la valeur SlideLayoutType.Custom de layoutType ne contient aucun espace réservé ni aucune forme. 2) L’équivalent de cette méthode est la méthode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessible via la propriété ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.