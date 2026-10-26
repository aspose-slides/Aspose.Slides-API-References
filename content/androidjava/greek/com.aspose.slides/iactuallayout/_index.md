---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Καθορίζει την πραγματική θέση ενός στοιχείου διαγράμματος.
type: docs
url: /el/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Καθορίζει την πραγματική θέση ενός στοιχείου διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getActualX()](#getActualX--) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερά άνω γωνία του διαγράμματος. |
| [getActualY()](#getActualY--) | Καθορίζει το πραγματικό άνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερά άνω γωνία του διαγράμματος. |
| [getActualWidth()](#getActualWidth--) | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. |
| [getActualHeight()](#getActualHeight--) | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερά άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει float.

**Επιστρέφει:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Καθορίζει το πραγματικό άνω μέρος του στοιχείου διαγράμματος σε σχέση με την αριστερά άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει float.

**Επιστρέφει:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει float.

**Επιστρέφει:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάζει float.

**Επιστρέφει:**
float