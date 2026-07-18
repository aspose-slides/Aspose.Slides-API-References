---
title: InsertChart()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.
type: docs
weight: 53
url: /el/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) μέθοδος

Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος διαγράμματος που θα δημιουργηθεί. |
| x | **float** | Η x-συντεταγμένη του νέου διαγράμματος, σε points. |
| y | **float** | Η y-συντεταγμένη του νέου διαγράμματος, σε points. |
| width | **float** | Το πλάτος του νέου διαγράμματος, σε points. |
| height | **float** | Το ύψος του νέου διαγράμματος, σε points. |
| index | **int32_t** | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το νέο διάγραμμα στη συλλογή σχημάτων. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) μέθοδος

Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος διαγράμματος που θα δημιουργηθεί. |
| x | **float** | Η x-συντεταγμένη του νέου διαγράμματος, σε points. |
| y | **float** | Η y-συντεταγμένη του νέου διαγράμματος, σε points. |
| width | **float** | Το πλάτος του νέου διαγράμματος, σε points. |
| height | **float** | Το ύψος του νέου διαγράμματος, σε points. |
| index | **int32_t** | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το νέο διάγραμμα στη συλλογή σχημάτων. |
| initWithSample | **bool** | True για να αρχικοποιήσετε το νέο διάγραμμα με δείγμα δεδομένων σειράς και ρυθμίσεις· false για να δημιουργήσετε το διάγραμμα χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, κάτι που κάνει τη δημιουργία πιο γρήγορη. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Δείτε επίσης

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChart](../../../aspose.slides.charts/ichart/)
* Κλάση [IShapeCollection](../)
* Ονοματοχώρος [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)