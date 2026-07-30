---
title: Split()
second_title: Riferimento API Aspose.Slides per C++
description: Divide la stringa per carattere.
type: docs
weight: 768
url: /it/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const metodo

Divide la stringa per carattere.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | char_t | Carattere con cui dividere la stringa. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(char_t, int32_t, StringSplitOptions) const metodo

Divide la stringa per carattere.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | char_t | Carattere con cui dividere la stringa. |
| count | **int32_t** | Il numero massimo di sottostringhe da restituire. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(char_t, char_t, StringSplitOptions) const metodo

Divide la stringa per uno dei due caratteri.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorA | char_t | Primo carattere con cui dividere la stringa. |
| separatorB | char_t | Secondo carattere con cui dividere la stringa. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const metodo

Divide la stringa per uno dei caratteri specificati.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri separatori. Se vuoto, qualsiasi carattere di spaziatura è considerato un separatore. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const metodo

Divide la stringa per uno dei caratteri specificati.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri separatori. Se vuoto, qualsiasi carattere di spaziatura è considerato un separatore. |
| count | **int32_t** | Il numero massimo di sottostringhe da restituire. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(const String\&, StringSplitOptions) const metodo

Divide la stringa per sottostringa.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | const [String](../)\& | Sottostringa usata come separatore. Se vuota, il carattere di spaziatura è considerato separatore. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(const String\&, int, StringSplitOptions) const metodo

Divide la stringa per sottostringa.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separator | const [String](../)\& | Sottostringa usata come separatore. Se vuota, il carattere di spaziatura è considerato separatore. |
| count | int | Numero massimo di elementi nell'array dei risultati. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const metodo

Divide la stringa per sottostringa.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) di stringhe separatrici. Se vuoto, non viene effettuata alcuna divisione. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const metodo

Divide la stringa per sottostringa. Attualmente, supporta solo un array di separatori con zero o un elemento.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) di stringhe separatrici. Se vuoto, non viene effettuata alcuna divisione. |
| count | int | Numero massimo di elementi nell'array dei risultati. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opzioni di divisione. |

### Valore di ritorno

[Array](../../array/) di sottostringhe.

## Vedi anche

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)