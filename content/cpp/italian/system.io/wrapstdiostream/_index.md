---
title: WrapSTDIOStream()
second_title: Riferimento API Aspose.Slides per C++
description: "Funzione wrapper per flussi simili a std::basic_istream."
type: docs
weight: 469
url: /it/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) funzione

Funzione wrapper per flussi simili a std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | Flusso simile a std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modalità di wrapping |

### Valore di ritorno

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) funzione

Funzione wrapper per flussi simili a std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | Flusso simile a std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modalità di wrapping |

### Valore di ritorno

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) funzione

Funzione wrapper per flussi simili a std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | Flusso simile a std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modalità di wrapping |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Posizione da preferire come posizione di lettura e scrittura, se diverse |

### Valore di ritorno

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Vedi anche

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)