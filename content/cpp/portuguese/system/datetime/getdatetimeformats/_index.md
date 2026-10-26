---
title: GetDateTimeFormats()
second_title: Referência da API Aspose.Slides for C++
description: Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com um dos especificadores padrão de data e hora.
type: docs
weight: 547
url: /pt/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const método

Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com um dos especificadores de formato padrão de data e hora.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const método

Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com o especificador de formato padrão de data e hora especificado.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | char_t | Especificador de formato padrão de data e hora. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const método

Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com um dos especificadores de formato padrão de data e hora e com o provedor de formato especificado.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const método

Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com o especificador de formato padrão de data e hora especificado e o provedor de formato.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | char_t | Especificador de formato padrão de data e hora. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato. |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)