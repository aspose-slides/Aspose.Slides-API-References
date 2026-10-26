---
title: GetHeight()
second_title: Aspose.Slides για C++ API Reference
description: Επιστρέφει το διάστιχο της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο, στη τρέχουσα μονάδα ενός καθορισμένου αντικειμένου Graphics.
type: docs
weight: 14
url: /el/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) μέθοδος


Επιστρέφει το διάστιχο γραμμής της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο, στη τρέχουσα μονάδα ενός καθορισμένου αντικειμένου [Graphics](../../graphics/).

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Ένα αντικείμενο [Graphics](../../graphics/) που καθορίζει τις μονάδες μέτρησης |

## Font::GetHeight(float) μέθοδος


Επιστρέφει το ύψος της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο όταν σχεδιάζεται σε συσκευή εμφάνισης με την καθορισμένη κάθετη ανάλυση.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dpi | **float** | Η κάθετη ανάλυση της συσκευής εμφάνισης |

### Τιμή Επιστροφής

Το ύψος της γραμματοσειράς σε εικονοκύτταρα

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Graphics](../../graphics/)
* Κλάση [Font](../)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)