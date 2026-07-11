---
title: ISummaryZoomSection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει ένα αντικείμενο Summary Zoom Section σε ένα πλαίσιο Summary Zoom.
type: docs
url: /el/com.aspose.slides/isummaryzoomsection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Αντιπροσωπεύει ένα αντικείμενο Summary Zoom Section σε ένα πλαίσιο Summary Zoom.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTitle()](#getTitle--) | Επιστρέφει τον τίτλο κειμένου του αντικειμένου Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Επιστρέφει τον τίτλο κειμένου του αντικειμένου Summary Zoom Section. |
| [getDescription()](#getDescription--) | Επιστρέφει την κειμενική περιγραφή του αντικειμένου Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Επιστρέφει την κειμενική περιγραφή του αντικειμένου Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Επιστρέφει τον τίτλο κειμένου του αντικειμένου Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Επιστρέφει:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Επιστρέφει τον τίτλο κειμένου του αντικειμένου Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Επιστρέφει την κειμενική περιγραφή του αντικειμένου Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Επιστρέφει:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Επιστρέφει την κειμενική περιγραφή του αντικειμένου Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |