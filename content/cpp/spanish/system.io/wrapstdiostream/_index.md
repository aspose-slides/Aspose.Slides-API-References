---
title: WrapSTDIOStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Función contenedora para flujos tipo std::basic_istream."
type: docs
weight: 469
url: /es/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) función

Función contenedora para flujos tipo std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | flujo tipo std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modo de envoltura |

### Valor devuelto

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) envoltorio

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) función

Función contenedora para flujos tipo std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | flujo tipo std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modo de envoltura |

### Valor devuelto

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) envoltorio

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) función

Función contenedora para flujos tipo std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | flujo tipo std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modo de envoltura |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Posición que se preferirá como posición de lectura y escritura, si son diferentes |

### Valor devuelto

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) envoltorio

## Véase también

* Enumeración [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enumeración [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Definición de tipo [SharedPtr](../../system/sharedptr/)
* Clase [Stream](../stream/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)