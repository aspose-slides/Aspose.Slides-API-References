---
title: StringFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe StringFormat.
type: docs
weight: 1
url: /it/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() costruttore

Crea una nuova istanza della classe [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) costruttore

Crea una nuova istanza della classe [StringFormat](../) con i flag di formato specificati e la lingua.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Una combinazione bitwise del valore enum StringFormatFlags che specifica il formato della stringa da rappresentare dall'oggetto creato |
| language | **int32_t** | Una lingua del testo |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) costruttore

Costruttore di copia.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Un oggetto [StringFormat](../) da cui copiare |

## Vedi anche

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [StringFormat](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)