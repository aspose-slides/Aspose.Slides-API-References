---
title: operator+()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma nova instância da classe Decimal que representa um valor que é a soma do valor especificado e do valor representado pelo objeto Decimal especificado.
type: docs
weight: 2185
url: /pt/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) função

Retorna uma nova instância da classe [Decimal](../decimal/) que representa um valor que é a soma do valor especificado e do valor representado pelo objeto [Decimal](../decimal/) especificado.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const T\& | The first summand |
| d | const [Decimal](../decimal/)\& | The constant reference to the [Decimal](../decimal/) object representing the second summand |

### Valor de Retorno

Uma nova instância da classe [Decimal](../decimal/) que representa um valor que é a soma de **x** e do valor representado por **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) função

Conecta todos os callbacks do delegate da mão direita ao final da lista de callbacks do delegate da mão esquerda.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate to which callbacks are added. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks are being added. |

### Valor de Retorno

Retorna um delegate que contém os callbacks do valor da mão esquerda e, em seguida, os da mão direita.

## System::operator+(const T1\&, const Nullable\<T2\>\&) função

Somar valores não anuláveis e anuláveis.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Right operand. |

### Valor de Retorno

Resultado da soma.

## System::operator+(T\&, const String\&) função

[String](../string/) concatenação.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [String](../string/) tipo literal. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | T\& | Literal a concatenar à string. |
| right | const [String](../string/)\& | [String](../string/) a concatenar. |

### Valor de Retorno

String concatenada.

## System::operator+(T\&, const String\&) função

[String](../string/) concatenação.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [String](../string/) tipo de ponteiro. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | T\& | [String](../string/) ponteiro a concatenar à string. |
| right | const [String](../string/)\& | [String](../string/) a concatenar. |

### Valor de Retorno

String concatenada.

## System::operator+(const char_t, const String\&) função

[String](../string/) concatenação.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | const char_t | Caractere a concatenar à string. |
| right | const [String](../string/)\& | [String](../string/) a concatenar. |

### Valor de Retorno

String concatenada.

## Veja Também

* Classe [Decimal](../decimal/)
* Classe [Nullable](../nullable/)
* Classe [String](../string/)
* Estrutura [IsStringLiteral](../isstringliteral/)
* Estrutura [IsStringPointer](../isstringpointer/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)