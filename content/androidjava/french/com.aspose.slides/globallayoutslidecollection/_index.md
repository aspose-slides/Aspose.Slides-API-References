---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de toutes les diapositives de mise en page dans la présentation.
type: docs
url: /fr/com.aspose.slides/globallayoutslidecollection/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Représente une collection de toutes les diapositives de mise en page dans la présentation. Étend la classe LayoutSlideCollection avec des méthodes d'ajout/duplication de diapositives de mise en page dans le contexte de l’unification des collections individuelles des diapositives de mise en page du maître.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Ajoute une nouvelle diapositive de mise en page à la présentation. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à dupliquer. |
|  |  |  |

--------------------

Lors du clonage d'une mise en page entre différentes présentations, le maître de la mise en page peut également être cloné afin de conserver le formatage source. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de plusieurs clones du même maître de diapositive. Le clonage manuel des diapositives maîtres ne sera ni empêché ni enregistré. |

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositive à dupliquer. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive maître pour une nouvelle mise en page. |
|  |  |  |

--------------------

1) La nouvelle mise en page sera liée au maître défini dans la présentation de destination. Il s'agit donc d'un analogue de copier/coller avec l'option « Utiliser le thème de destination » dans PowerPoint. 2) Un analogue de cette méthode est la méthode [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) accessible via la propriété ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Ajoute une nouvelle diapositive de mise en page à la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive maître pour une nouvelle mise en page. |
| layoutType | byte | Type de mise en page pour une nouvelle mise en page. Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée. Si le paramètre null est fourni, le nom sera généré automatiquement en fonction du type de mise en page fourni (par exemple « Title Slide » ou « 1\_Title Slide », « 2\_.. », etc.). |
|  |  |  |

--------------------

1) La mise en page ajoutée pour la valeur SlideLayoutType.Custom de layoutType ne contient aucun espace réservé ni aucune forme. 2) Un analogue de cette méthode est la méthode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessible via la propriété ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositive ajoutée.