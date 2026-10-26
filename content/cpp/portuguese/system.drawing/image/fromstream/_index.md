---
title: FromStream()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um objeto Image a partir do fluxo especificado.
type: docs
weight: 339
url: /pt/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) método

Cria um objeto [Image](../) a partir do fluxo especificado.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Um fluxo que contém dados de imagem |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Valor de Retorno

Um ponteiro compartilhado para o objeto [Image](../) criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../)
* Classe [Stream](../../../system.io/stream/)
* Espaço de nomes [System::Drawing](../../)
* Library [Aspose.Slides](../../../)