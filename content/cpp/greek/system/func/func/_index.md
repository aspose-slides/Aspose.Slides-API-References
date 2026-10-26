---
title: Func()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κατασκευαστής προεπιλογής που δημιουργεί null-Func.
type: docs
weight: 1
url: /el/system/func/func/
---
## Func::Func() κατασκευαστής

Κατασκευαστής προεπιλογής που δημιουργεί null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) κατασκευαστής

Κατασκευαστής που δημιουργεί το αντικείμενο [Func](../) και αναθέτει τιμή (είτε πραγματικό callback είτε nullptr) σε αυτό.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος ορίσματος. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T\&& | Όρισμα. |

## Func::Func(const Func\&) κατασκευαστής

Κατασκευαστής αντιγραφής.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) για αντιγραφή δεδομένων από. |

## Func::Func(Func\&&) κατασκευαστής

Κατασκευαστής μετακίνησης.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) για μετακίνηση δεδομένων από. |

## Δείτε επίσης

* Κλάση [Func](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)