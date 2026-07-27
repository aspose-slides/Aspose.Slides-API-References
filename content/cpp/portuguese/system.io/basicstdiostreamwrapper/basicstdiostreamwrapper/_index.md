---
title: BasicSTDIOStreamWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /pt/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) construtor


Constrói uma nova instância de [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | A referência ao fluxo |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Modo de encapsulamento |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Posição que será preferida como posição de leitura e escrita, se forem diferentes |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) construtor


Construtor de cópia. Excluído.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## Veja Também

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* classe [BasicSTDIOStreamWrapper](../)
* namespace [System::IO](../../)
* biblioteca [Aspose.Slides](../../../)