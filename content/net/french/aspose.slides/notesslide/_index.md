---
title: NotesSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une diapositive de notes dans une présentation.
type: docs
weight: 8870
url: /fr/aspose.slides/notesslide/
---

## Classe NotesSlide

Représente une diapositive de notes dans une présentation.

```csharp
public class NotesSlide : BaseSlide, INotesSlide
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Renvoie l'arrière-plan de la diapositive. En lecture seule [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Renvoie la collection de contrôles ActiveX sur une diapositive. En lecture seule [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Renvoie les données personnalisées de la diapositive. En lecture seule [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/notesslide/headerfootermanager) { get; } | Renvoie le gestionnaire d'en-têtes et de pieds de page de la diapositive de notes. En lecture seule [`INotesSlideHeaderFooterManager`](../inotesslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fournit un accès facile aux hyperliens contenus. En lecture seule [`IHyperlinkQueries`](../ihyperlinkqueries). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Renvoie ou définit le nom d'une diapositive. Lecture/écriture String. |
| [NotesTextFrame](../../aspose.slides/notesslide/notestextframe) { get; } | Renvoie un TextFrame contenant le texte des notes s'il y en a un. En lecture seule [`ITextFrame`](../itextframe). |
| [ParentSlide](../../aspose.slides/notesslide/parentslide) { get; } | Renvoie la diapositive parent. En lecture seule [`ISlide`](../islide). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Renvoie l'interface IPresentation. En lecture seule [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Renvoie les formes d'une diapositive. En lecture seule [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/notesslide/showmastershapes) { get; set; } | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non. Lecture/écriture Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Renvoie l'ID d'une diapositive. En lecture seule UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Renvoie l'objet Transition qui contient des informations sur la façon dont la diapositive spécifiée avance pendant un diaporama. En lecture seule [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/notesslide/thememanager) { get; } | Renvoie le gestionnaire de thème de substitution. En lecture seule [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Renvoie l'objet de chronologie d'animation. En lecture seule [`IAnimationTimeLine`](../ianimationtimeline). |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Renvoie un thème effectif pour cette diapositive. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Détermine si les deux instances de IBaseSlide sont égales. La valeur de retour est calculée en fonction de la structure et du contenu statique de la diapositive. Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiant unique, par exemple SlideId, et le contenu dynamique, par exemple la valeur de la date actuelle dans le champ de date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Joint les passages avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Joint les passages avec le même formatage dans tous les paragraphes dans toutes les formes acceptables. |

### Voir aussi

* classe [BaseSlide](../baseslide)
* interface [INotesSlide](../inotesslide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->