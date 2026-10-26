---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides για το API αναφοράς C++
description: Δημιουργεί ένα νέο αντικείμενο του BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /el/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο του [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Η αναφορά στη ροή |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Λειτουργία περιτύλιξης |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Θέση που θα προτιμάται ως θέση ανάγνωσης και εγγραφής, αν είναι διαφορετικές |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) κατασκευαστής

Κατασκευαστής αντιγραφής. Διαγραμμένος.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## Δείτε επίσης

* Απαρίθμηση [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Απαρίθμηση [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Ορισμός τύπου [char_type](../../stdiostreamwrapperbase/char_type/)
* Ορισμός τύπου [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Κλάση [BasicSTDIOStreamWrapper](../)
* Ονοματοχώρος [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)