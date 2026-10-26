---
title: Wait()
second_title: Aspose.Slides for C++ Αναφορά API
description: Αποδεσμεύει το κλείδωμα ενός αντικειμένου και μπλοκάρει το τρέχον νήμα μέχρι να επανακτήσει το κλείδωμα. Εάν λήξει το καθορισμένο διάστημα λήξης χρόνου, το νήμα εισέρχεται στην ουρά ετοιμότητας. Προαιρετικά εξέρχεται από τον τομέα συγχρονισμού για το συγχρονισμένο περιβάλλον πριν από την αναμονή και επανακτά τον τομέα μετά. Δεν υλοποιείται.
type: docs
weight: 53
url: /el/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) μέθοδος

Αποδεσμεύει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επανακτήσει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης χρόνου λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Προαιρετικά εξέρχεται από τον τομέα συγχρονισμού για το συγχρονισμένο συμφραζόμενο πριν από την αναμονή και επανακτά τον τομέα μετά. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) μέθοδος

Αποδεσμεύει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επανακτήσει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης χρόνου λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Προαιρετικά εξέρχεται από τον τομέα συγχρονισμού για το συγχρονισμένο συμφραζόμενο πριν από την αναμονή και επανακτά τον τομέα μετά. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) μέθοδος

Αποδεσμεύει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επανακτήσει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης χρόνου λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) μέθοδος

Αποδεσμεύει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επανακτήσει το κλείδωμα. Εάν το καθορισμένο διάστημα λήξης χρόνου λήξει, το νήμα εισέρχεται στην ουρά ετοιμότητας. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::Wait(const SharedPtr\<Object\>\&) μέθοδος

Αποδεσμεύει το κλείδωμα σε ένα αντικείμενο και μπλοκάρει το τρέχον νήμα μέχρι να επανακτήσει το κλείδωμα. Δεν υλοποιείται.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Monitor](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Χώρος ονομάτων [System::Threading](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)