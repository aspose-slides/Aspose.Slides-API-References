---
title: IVbaModuleCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de módulos de um Projeto VBA.
type: docs
url: /pt/com.aspose.slides/ivbamodulecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Representa uma coleção de módulos de um Projeto VBA.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Adiciona um novo módulo vazio ao Projeto VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Remove a primeira ocorrência de um objeto específico da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Adiciona um novo módulo vazio ao Projeto VBA.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome do módulo |

**Retorno:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Módulo adicionado.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | O módulo a ser removido da coleção. |