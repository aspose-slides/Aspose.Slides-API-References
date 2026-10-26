---
title: AddPath()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o caminho especificado ao caminho representado pelo objeto atual.
type: docs
weight: 222
url: /pt/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) método

Adiciona o caminho especificado ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | O caminho a ser adicionado |
| connect | **bool** | True especifica que a última primeira figura no **path** é parte da última figura do caminho representado pelo objeto atual; false especifica que a primeira figura no **path** e a última figura do caminho representado pelo objeto atual são figuras separadas |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)