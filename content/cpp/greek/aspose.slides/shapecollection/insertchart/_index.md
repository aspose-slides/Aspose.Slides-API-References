---
title: InsertChart()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δεδομένα δειγματικών σειρών και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.
type: docs
weight: 92
url: /el/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) μέθοδος

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δεδομένα δειγματικών σειρών και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος του γραφήματος που θα δημιουργηθεί. |
| x | **float** | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | **float** | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | **float** | Το πλάτος του νέου γραφήματος, σε points. |
| height | **float** | Το ύψος του νέου γραφήματος, σε points. |
| index | **int32_t** | Ο μηδενικά-βασισμένος δείκτης όπου θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) μέθοδος

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δεδομένα δειγματικών σειρών και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος του γραφήματος που θα δημιουργηθεί. |
| x | **float** | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | **float** | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | **float** | Το πλάτος του νέου γραφήματος, σε points. |
| height | **float** | Το ύψος του νέου γραφήματος, σε points. |
| index | **int32_t** | Ο μηδενικά-βασισμένος δείκτης όπου θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |
| initWithSample | **bool** | True για να αρχικοποιηθεί το νέο γράφημα με δεδομένα δειγματικών σειρών και ρυθμίσεις· false για να δημιουργηθεί το γράφημα χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, γεγονός που επιταχύνει τη δημιουργία. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Δείτε επίσης

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChart](../../../aspose.slides.charts/ichart/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)