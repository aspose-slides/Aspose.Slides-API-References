---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Armazena fontes definidas no tema.
type: docs
url: /pt/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Armazena fontes definidas no tema.
## Métodos

| Método | Descrição |
| --- | --- |
| [getMinor()](#getMinor--) | Retorna a coleção de fontes para a parte "corpo" do slide. |
| [getMajor()](#getMajor--) | Retorna a coleção de fontes para a parte "cabeçalho" do slide. |
| [getName()](#getName--) | Retorna o nome do esquema de fontes. |
| [setName(String value)](#setName-java.lang.String-) | Retorna o nome do esquema de fontes. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Retorna a coleção de fontes para a parte "corpo" do slide. Somente leitura [IFonts](../../com.aspose.slides/ifonts).

**Retorna:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Retorna a coleção de fontes para a parte "cabeçalho" do slide. Somente leitura [IFonts](../../com.aspose.slides/ifonts).

**Retorna:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Retorna o nome do esquema de fontes. Leitura/gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Retorna o nome do esquema de fontes. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |