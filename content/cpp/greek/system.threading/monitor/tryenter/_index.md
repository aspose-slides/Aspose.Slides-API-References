---
title: TryEnter()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσπάθεια για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν υλοποιείται.
type: docs
weight: 27
url: /el/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) μέθοδος


Προσπάθεια για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) μέθοδος


Προσπάθεια για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο και ατομική ρύθμιση μιας τιμής που υποδεικνύει εάν το κλείδωμα λήφθηκε.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) μέθοδος


Προσπάθεια, για τον καθορισμένο αριθμό χιλιοστών δευτερολέπτων, για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) μέθοδος


Προσπάθεια, για την καθορισμένη διάρκεια χρόνου, για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) μέθοδος


Προσπάθεια, για την καθορισμένη διάρκεια χρόνου, για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο και ατομική ρύθμιση μιας τιμής που υποδεικνύει εάν το κλείδωμα λήφθηκε.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) μέθοδος


Προσπάθεια, για την καθορισμένη διάρκεια χρόνου, για απόκτηση αποκλειστικού κλειδώματος στο καθορισμένο αντικείμενο και ατομική ρύθμιση μιας τιμής που υποδεικνύει εάν το κλείδωμα λήφθηκε.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Monitor](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)