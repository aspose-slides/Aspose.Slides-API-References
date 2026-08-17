---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides για την τεκμηρίωση API Java
description: Αντιπροσωπεύει τη συλλογή των ομάδων συνδυάσιμων σειρών.
type: docs
url: /el/com.aspose.slides/ichartseriesgroupcollection/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Αναπαριστά τη συλλογή των ομάδων συνδυάσιμων σειρών.

--------------------

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε στον κύριο άξονα είτε στον δευτερεύοντα άξονα (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Συνεπώς, η αρχή ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τους τύπους που αναφέρονται παραπάνω και κατά τον τύπο σχεδίασης κύριου/δευτερεύοντος άξονα. 2) Η ομάδα σειρών περιέχει ορισμένα χαρακτηριστικά σειρών που είναι κοινά για κάθε σειρά στην ομάδα (« χαρακτηριστικά ομάδας σειρών »). Τα « χαρακτηριστικά ομάδας σειρών » στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε ένα από τα « χαρακτηριστικά ομάδας σειρών » μπορεί να έχει μια προβολή μόνο-ανάγνωση στην κλάση ChartSeries.

## Μεθόδους

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Gets the series group by series. |
| [get_Item(int index)](#get-Item-int-) | Gets the series group by index. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Λαμβάνει την ομάδα σειρών με βάση τη σειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Επιστρέφει:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

Λαμβάνει την ομάδα σειρών με βάση το ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)