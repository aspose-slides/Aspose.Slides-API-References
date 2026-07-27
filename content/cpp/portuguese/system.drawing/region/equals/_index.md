---
title: Equals()
second_title: Aspose.Slides para C++ – Referência da API
description: Determina se a região especificada é idêntica à região representada pelo objeto atual na superfície de desenho especificada.
type: docs
weight: 157
url: /pt/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) método

Determina se a região especificada é idêntica à região representada pelo objeto atual na superfície de desenho especificada.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | A região a ser comparada com esta região |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Uma superfície de desenho |

### Valor de Retorno

Verdadeiro se o interior da região especificada for idêntico ao interior da região representada pelo objeto atual quando a transformação associada ao parâmetro **g** for aplicada; caso contrário - falso

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../)
* Classe [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)