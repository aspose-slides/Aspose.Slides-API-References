---
title: WrapSTDIOStream()
second_title: Referência da API Aspose.Slides para C++
description: "Função wrapper para fluxos do tipo std::basic_istream."
type: docs
weight: 469
url: /pt/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function


Função wrapper para fluxos do tipo std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | Fluxo do tipo std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modo de encapsulamento |

### Valor de Retorno

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function


Função wrapper para fluxos do tipo std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | Fluxo do tipo std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modo de encapsulamento |

### Valor de Retorno

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function


Função wrapper para fluxos do tipo std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | Fluxo do tipo std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Modo de encapsulamento |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Posição que será preferida como posição de leitura e escrita, se forem diferentes |

### Valor de Retorno

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## Veja Também

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)