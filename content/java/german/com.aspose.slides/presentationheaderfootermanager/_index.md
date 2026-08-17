---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Manager dar, der das Verhalten aller Fußzeilen-Datum-Uhrzeit- und Foliennummer-Platzhalter einer Präsentation verwaltet.
type: docs
url: /de/com.aspose.slides/presentationheaderfootermanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten aller Fußzeilen-, Datum-Uhrzeit- und Foliennummer-Platzhalter einer Präsentation verwaltet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Changes all header placeholders visibility, including notes master, notes slides and handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Changes all footer placeholders visibility, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Changes all page number placeholders visibility, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Changes all date-time placeholders visibility, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sets text to all header placeholders, including notes master, notes slides and handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sets text to all footer placeholders, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sets text to all date-time placeholders, including master slides, layout slides, slides, notes master, notes slides and handout master. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Kopfzeilen-Platzhalter, einschließlich Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Kopfzeilen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |
### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Fußzeilen-Platzhalter, einschließlich Master-Folien, Layout-Folien, Folien, Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Fußzeilen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |
### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Foliennummer-Platzhalter, einschließlich Master-Folien, Layout-Folien, Folien, Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Foliennummer-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |
### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Datum-Uhrzeit-Platzhalter, einschließlich Master-Folien, Layout-Folien, Folien, Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datum-Uhrzeit-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |
### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

Setzt Text für alle Kopfzeilen-Platzhalter, einschließlich Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu setzende Text. |
### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

Setzt Text für alle Fußzeilen-Platzhalter, einschließlich Master-Folien, Layout-Folien, Folien, Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu setzende Text. |
### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

Setzt Text für alle Datum-Uhrzeit-Platzhalter, einschließlich Master-Folien, Layout-Folien, Folien, Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu setzende Text. |
### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändert die Sichtbarkeit der Fußzeilen-, Datum-Uhrzeit- und Foliennummer-Platzhalter für alle Titelfolien und für die erste Layout-Folie. Titelfolien \\u2013 Folien, die auf der ersten Layout-Folie basieren (unabhängig vom Typ dieser ersten Layout-Folie).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |