---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τη συλλογή των ομάδων συνδυάσιμων σειρών.
type: docs
url: /el/com.aspose.slides/ichartseriesgroupcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Αντιπροσωπεύει τη συλλογή των ομάδων συνδυάσιμων σειρών.

--------------------

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες των συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε πρωτεύοντες άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τους τύπους ομάδων που αναφέρθηκαν παραπάνω και κατά τύπο σχεδίασης πρωτεύοντος/δευτερεύοντος άξονα.

## Μεθόδοι

| Method | Description |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Λαμβάνει την ομάδα σειράς βάσει σειράς. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει την ομάδα σειράς βάσει δείκτη. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Λαμβάνει την ομάδα σειράς βάσει σειράς.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Επιστρέφει:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

Λαμβάνει την ομάδα σειράς βάσει δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)