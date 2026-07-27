---
title: StringFormat()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe StringFormat.
type: docs
weight: 1
url: /pt/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() construtor

Constrói uma nova instância da classe [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) construtor

Constrói uma nova instância da classe [StringFormat](../) com as flags de formato especificadas e o idioma.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Uma combinação bit a bit dos valores da enumeração StringFormatFlags que especifica o formato de string a ser representado pelo objeto sendo criado |
| language | **int32_t** | Um idioma do texto |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) construtor

Construtor de cópia.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Um objeto [StringFormat](../) a ser copiado |

## Ver Também

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [StringFormat](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)