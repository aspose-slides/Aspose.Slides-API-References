---
title: ColorOperation
second_title: Referência da API Aspose.Slides para Java
description: Representa diferentes operações de cor usadas para transformações de cor.
type: docs
url: /pt/com.aspose.slides/coloroperation/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Representa diferentes operações de cor usadas para transformações de cor. Objeto imutável.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Cria uma nova operação de transformação de cor. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Cria uma nova operação de transformação de cor. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getOperationType()](#getOperationType--) | Retorna ou define o tipo de uma operação. |
| [getParameter()](#getParameter--) | Retorna um parâmetro de uma operação. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se as duas instâncias de ColorOperation são iguais. |
| [hashCode()](#hashCode--) | Funciona como uma função hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela hash. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Cria uma nova operação de transformação de cor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| op | int | Tipo de operação. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Cria uma nova operação de transformação de cor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| op | int | Tipo de operação. |
| parameter | float | Parâmetro da operação. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Retorna ou define o tipo de uma operação. Somente leitura [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Retorna:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Retorna um parâmetro de uma operação. Somente leitura float.

**Retorna:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se as duas instâncias de ColorOperation são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O ColorOperation a comparar com o ColorOperation atual. |

**Retorna:**
boolean - **true** se o ColorOperation especificado for igual ao ColorOperation atual; caso contrário, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funciona como uma função hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela hash.

**Retorna:**
int