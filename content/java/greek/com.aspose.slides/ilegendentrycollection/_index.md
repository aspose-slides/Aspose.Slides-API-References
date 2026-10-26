---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά τη συλλογή υπομνημάτων.
type: docs
url: /el/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Αναπαριστά τη συλλογή υπομνημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά τις ιδιότητες της καταχώρησης υπομνήματος που αντιστοιχεί στο Chart.ChartData.Series[0].DataPoints[index] στην περίπτωση τύπου διαγράμματος από αυτήν τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie· ή στην περίπτωση που αντιστοιχεί στο Chart.ChartData.Series[index] για άλλους τύπους διαγραμμάτων. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό των στοιχείων που περιέχονται στην συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Αποκτά τις ιδιότητες της καταχώρησης υπομνήματος που αντιστοιχεί στο Chart.ChartData.Series[0].DataPoints[index] στην περίπτωση τύπου διαγράμματος από αυτήν τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie· ή στην περίπτωση που αντιστοιχεί στο Chart.ChartData.Series[index] για άλλους τύπους διαγραμμάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Αποκτά τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int