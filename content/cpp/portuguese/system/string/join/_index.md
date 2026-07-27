---
title: Join()
second_title: Referência da API Aspose.Slides para C++
description: Junta o array usando a string como separador.
type: docs
weight: 846
url: /pt/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) método

Junta o array usando a string como separador.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre os elementos do array ao juntá-los. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de partes a juntar. |
| startIndex | int | Primeiro índice no array de onde começar a juntar. |
| count | int | Número de elementos do array a juntar. -1 significa 'até o final do array'. |

### Valor de retorno

[String](../) representando os elementos do array juntados.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) método

Junta o array usando a string como separador.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre os elementos do array ao juntá-los. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView de partes a juntar. |
| startIndex | int | Primeiro índice no array de onde começar a juntar. |
| count | int | Número de elementos do array a juntar. -1 significa 'até o final do array'. |

### Valor de retorno

[String](../) representando os elementos do array juntados.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) método

Junta o array usando a string como separador.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre os elementos do array ao juntá-los. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - objeto enumerável de partes |

### Valor de retorno

[String](../) representando os elementos juntados.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) método

Junta o array usando a string como separador.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) para colocar entre os elementos do array ao juntá-los. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) de partes a juntar. |

### Valor de retorno

[String](../) representando os elementos juntados.

## Ver também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)