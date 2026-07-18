---
title: WrapSTDIOStream()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Συνάρτηση περιτύλιξης για ροές τύπου std::basic_istream."
type: docs
weight: 469
url: /el/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) συνάρτηση


Συνάρτηση περιτύλιξης για ροές τύπου std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-like stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Λειτουργία περιτύλιξης |

### Τιμή Επιστροφής

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) περιτύλιγμα

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) συνάρτηση


Συνάρτηση περιτύλιξης για ροές τύπου std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-like stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Λειτουργία περιτύλιξης |

### Τιμή Επιστροφής

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) περιτύλιγμα

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) συνάρτηση


Συνάρτηση περιτύλιξης για ροές τύπου std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-like stream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Λειτουργία περιτύλιξης |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Θέση που θα προτιμηθεί ως θέση ανάγνωσης και εγγραφής, αν είναι διαφορετικές |

### Τιμή Επιστροφής

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) περιτύλιγμα

## Δείτε επίσης

* Απαρίθμηση [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Απαρίθμηση [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Καθορισμός τύπου [SharedPtr](../../system/sharedptr/)
* Κλάση [Stream](../stream/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)