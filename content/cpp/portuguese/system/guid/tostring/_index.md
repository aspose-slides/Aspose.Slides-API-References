---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Converte o GUID representado pelo objeto atual para sua representação em forma de string.
type: docs
weight: 79
url: /pt/system/guid/tostring/
---
## Guid::ToString() const método


Converte o GUID representado pelo objeto atual para sua representação em forma de string.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const método


Converte o GUID representado pelo objeto atual para sua representação em forma de string usando o formato de string especificado.

```cpp
String System::Guid::ToString(const String &format) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../string/)\& | O formato a ser usado |

### Valor de Retorno

A representação em forma de string do valor GUID representado pelo objeto atual

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const método


Converte o GUID representado pelo objeto atual para sua representação em forma de string usando o formato de string especificado e a cultura.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../string/)\& | O formato a ser usado |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada |

### Valor de Retorno

A representação em forma de string do valor GUID representado pelo objeto atual

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Guid](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)