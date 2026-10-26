---
title: AddChart()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 27
url: /el/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος του διαγράμματος προς προσθήκη. |
| x | **float** | Η τιμή x του νέου διαγράμματος, σε σημεία. |
| y | **float** | Η τιμή y του νέου διαγράμματος, σε σημεία. |
| width | **float** | Το πλάτος του διαγράμματος, σε σημεία. |
| height | **float** | Το ύψος του διαγράμματος, σε σημεία. |

### Τιμή επιστροφής

Το πρόσφατα δημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος του διαγράμματος προς προσθήκη. |
| x | **float** | Η τιμή x του νέου διαγράμματος, σε σημεία. |
| y | **float** | Η τιμή y του νέου διαγράμματος, σε σημεία. |
| width | **float** | Το πλάτος του διαγράμματος, σε σημεία. |
| height | **float** | Το ύψος του διαγράμματος, σε σημεία. |
| initWithSample | **bool** | True για την αρχικοποίηση του νέου διαγράμματος με δείγμα δεδομένων σειράς και ρυθμίσεις· false για τη δημιουργία του διαγράμματος χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, κάτι που κάνει τη δημιουργία ταχύτερη. |

### Τιμή επιστροφής

Το πρόσφατα δημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Δείτε επίσης

* Απαρίθμηση [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChart](../../../aspose.slides.charts/ichart/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)