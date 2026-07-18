---
title: FontFallBackRule()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί νέα παρουσία.
type: docs
weight: 66
url: /el/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) constructor

Δημιουργεί νέα παρουσία.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Παραμέτροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **uint32_t** | Δείκτης έναρξης του εύρους unicode |
| endIndex | **uint32_t** | Δείκτης λήξης του εύρους unicode |
| fontNames | [System::String](../../../system/string/) | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |
## Σχόλια

```cpp
// Δημιουργεί νέα παρουσία του FantFallBackRule με μία γραμματοσειρά.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Δημιουργεί νέα παρουσία του FantFallBackRule με πολλές γραμματοσειρές.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) constructor

Δημιουργεί νέα παρουσία.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Παραμέτροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **uint32_t** | Δείκτης έναρξης του εύρους unicode |
| endIndex | **uint32_t** | Δείκτης λήξης του εύρους unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |
## Σχόλια

```cpp
// Δημιουργεί νέα παρουσία του FantFallBackRule με δύο γραμματοσειρές
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Δημιουργεί νέα παρουσία του FantFallBackRule με πολλές γραμματοσειρές.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [FontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)