---
title: LegendEntryCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει τη συλλογή των υπομνημάτων.
type: docs
url: /el/com.aspose.slides/legendentrycollection/
---
**Κληρονομικότητα:**  
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)  
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Αντιπροσωπεύει τη συλλογή των υπομνημάτων.

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει τις ιδιότητες της εγγραφής υπομνήματος που αντιστοιχεί στο Chart.ChartData.Series[0].DataPoints[index] σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; ή που αντιστοιχεί στο Chart.ChartData.Series[index] για άλλους τύπους διαγράμματος. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των εγγραφών υπομνήματος. |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Λαμβάνει τις ιδιότητες της εγγραφής υπομνήματος που αντιστοιχεί στο Chart.ChartData.Series[0].DataPoints[index] σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; ή που αντιστοιχεί στο Chart.ChartData.Series[index] για άλλους τύπους διαγράμματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public final int getCount()
```

Λαμβάνει τον αριθμό των εγγραφών υπομνήματος. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int