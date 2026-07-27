---
title: String()
second_title: Referência da API Aspose.Slides para C++
description: Construtor padrão. Cria um objeto string que é considerado nulo.
type: docs
weight: 14
url: /pt/system/string/string/
---
## String::String() construtor

Construtor padrão. Cria um objeto string que é considerado nulo.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) construtor

Constrói string com base em literal de string. Considera o literal como uma string terminada em null, calcula o comprimento da string de destino com base no tamanho do literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T\& | [String](../) ponteiro literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) construtor

Constrói string com base em ponteiro de string de caracteres. Trata a string apontada como terminada em null, calcula o comprimento da string de destino com base no caractere nulo.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | Ponteiro de string de caracteres. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) construtor

Constrói string com base em literal de string. Considera o literal como uma string terminada em null em UTF8, calcula o comprimento da string de destino com base no tamanho do literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T\& | [String](../) ponteiro literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) construtor

Constrói string com base em ponteiro de string de caracteres. Trata a string apontada como terminada em null em UTF8, calcula o comprimento da string de destino com base no caractere nulo.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | Ponteiro de string de caracteres. |

## String::String(const char16_t *, int) construtor

Constrói string a partir de ponteiro de string de caracteres e comprimento explícito.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const char16_t * | [String](../) ponteiro, pode ser literal ou array. |
| length | int | Comprimento explícito da string |

## String::String(const ReadOnlySpan\<char16_t\>\&) construtor

Inicializa uma nova instância da classe [System.String](../) com os caracteres Unicode indicados no span somente leitura especificado.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Um span somente leitura de caracteres Unicode. |

## String::String(const char *, int) construtor

Constrói string a partir de ponteiro de string de caracteres e comprimento explícito.

```cpp
System::String::String(const char *str, int length)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const char * | [String](../) ponteiro para os dados UTF8, pode ser literal ou array. |
| length | int | Comprimento explícito da string |

## String::String(const char16_t *, int, int) construtor

Constrói string a partir de ponteiro de string de caracteres a partir da posição inicial usando o comprimento.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const char16_t * | [String](../) ponteiro, pode ser literal ou array. |
| start | int | Posição inicial. |
| length | int | [String](../) comprimento. |

## String::String(const char16_t, int) construtor

Construtor de preenchimento.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ch | const char16_t | Caractere de preenchimento. |
| count | int | Comprimento alvo. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) construtor

Construtor nullptr. Declarado como template para resolver prioridades com outros construtores template.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Parâmetros de Template

| Parâmetro | Descrição |
| --- | --- |
| T | Deve ser nullptr_t |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) construtor

Constrói string com base em literal widestring. Considera o literal como uma string terminada em null, calcula o comprimento da string de destino com base no tamanho do literal. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T\& | [String](../) ponteiro literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) construtor

Constrói string com base em ponteiro de string widecharacter. Trata a string apontada como terminada em null, calcula o comprimento da string de destino com base no caractere nulo. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | Ponteiro de string de caracteres. |

## String::String(const wchar_t *, int) construtor

Constrói string a partir de ponteiro de string widecharacter e comprimento explícito. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) ponteiro, pode ser literal ou array. |
| length | int | Comprimento explícito da string |

## String::String(const wchar_t, int) construtor

Construtor de preenchimento. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ch | const **wchar_t** | Caractere de preenchimento. |
| count | int | Comprimento alvo. |

## String::String(const String\&) construtor

Construtor de cópia.

```cpp
System::String::String(const String &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a ser copiado. |

## String::String(String\&&) construtor

Construtor de movimentação.

```cpp
System::String::String(String &&str) noexcept
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) de onde mover os dados. |

## String::String(const ArrayPtr\<char16_t\>\&) construtor

Converte todo o array de caracteres para string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) a ser convertido em string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) construtor

Converte subintervalo de array de caracteres para string. Se os parâmetros estiverem fora dos limites do array, uma string vazia é construída.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Array de caracteres. |
| offset | int | Índice inicial do subarray. |
| len | int | Comprimento do subarray. |

## String::String(const codeporting_icu::UnicodeString\&) construtor

Envolve UnicodeString em [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString a ser envolvido em [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) construtor

Construtor de movimentação.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString a ser envolvido em [String](../). |

## String::String(const std::wstring\&) construtor

Cria [String](../) a partir de widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const std::wstring\& | Widestring a ser convertido em [String](../). |

## String::String(const std::u16string\&) construtor

Cria [String](../) a partir de string utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const std::u16string\& | String Utf16 a ser convertida em [String](../). |

## String::String(const std::string\&) construtor

Cria [String](../) a partir de string std::string apresentada no formato UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| utf8str | const std::string\& | String std::string a ser convertida em [String](../). |

## String::String(const std::u32string\&) construtor

Cria [String](../) a partir de string std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| u32str | const std::u32string\& | String std::u32string a ser convertida em [String](../). |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Classe [ReadOnlySpan](../../readonlyspan/)
* Estrutura [IsStringLiteral](../../isstringliteral/)
* Estrutura [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)