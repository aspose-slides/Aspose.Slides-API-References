---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents legends collection.
type: docs
url: /el/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Αντιπροσωπεί τη συλλογή υπομνοίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά τις ιδιότητες της εγγραφής υπομνίου που αντιστοιχεί στο Chart.ChartData.Series[0].DataPoints[index] σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie· ή που αντιστοιχεί στο Chart.ChartData.Series[index] για άλλους τύπους διαγράμματος. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Αποκτά τις ιδιότητες της εγγραφής υπομνίου που αντιστοιχεί στο Chart.ChartData.Series[0].DataPoints[index] σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie· ή που αντιστοιχεί στο Chart.ChartData.Series[index] για άλλους τύπους διαγράμματος.

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

Αποκτά τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int