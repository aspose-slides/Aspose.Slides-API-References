---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table.
type: docs
url: /pt/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Representa o formato de uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retorna um objeto de propriedades de preenchimento de tabela. |
| [getTransparency()](#getTransparency--) | Obtém ou define a transparência da cor de preenchimento. |
| [setTransparency(float value)](#setTransparency-float-) | Obtém ou define a transparência da cor de preenchimento. |
| [getEffective()](#getEffective--) | Obtém as propriedades de formatação efetiva da tabela com herança e estilos de tabela aplicados. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retorna um objeto de propriedades de preenchimento de tabela. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Obtém ou define a transparência da cor de preenchimento. Leitura/gravação  float .

**Retorna:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Obtém ou define a transparência da cor de preenchimento. Leitura/gravação  float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Obtém as propriedades de formatação efetiva da tabela com herança e estilos de tabela aplicados.

**Retorna:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Um [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).