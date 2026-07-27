---
title: GetHeight()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o espaçamento entre linhas da fonte representada pelo objeto atual, na unidade atual de um objeto Graphics especificado.
type: docs
weight: 14
url: /pt/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) método

Retorna o espaçamento entre linhas da fonte representada pelo objeto atual, na unidade atual de um objeto [Graphics](../../graphics/) especificado.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Um objeto [Graphics](../../graphics/) que especifica as unidades de medida |

## Font::GetHeight(float) método

Retorna a altura da fonte representada pelo objeto atual quando desenhada em um dispositivo de exibição com a resolução vertical especificada.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dpi | **float** | A resolução vertical do dispositivo de exibição |

### Valor de Retorno

A altura da fonte em pixels

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Graphics](../../graphics/)
* Classe [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)