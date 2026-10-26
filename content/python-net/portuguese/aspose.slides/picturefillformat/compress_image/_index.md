---
title: compress_image method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas.

### Retorna

Um **bool** indicando se a imagem foi comprimida com sucesso. Retorna **True** se a imagem foi redimensionada ou recortada, caso contrário **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Se verdadeiro, o método removerá as áreas recortadas da imagem, potencialmente reduzindo ainda mais seu tamanho. |
| resolution | [`PicturesCompression`](/slides/python-net/pt/aspose.slides.export/picturescompression) | A resolução alvo para compressão, especificada como um valor do enum [`PicturesCompression`](/slides/python-net/pt/aspose.slides.export/picturescompression). |

### Observações

Este método altera o tamanho e a resolução da imagem de forma semelhante ao recurso "Picture Format -> Compress Pictures" do PowerPoint.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando a resolução não é um valor válido. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas.

### Retorna

Um **bool** indicando se a imagem foi comprimida com sucesso. Retorna **True** se a imagem foi redimensionada ou recortada, caso contrário **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Se verdadeiro, o método removerá as áreas recortadas da imagem, potencialmente reduzindo ainda mais seu tamanho. |
| resolution | **float** | A resolução alvo em DPI. Este valor deve ser positivo e define como a imagem será redimensionada. |

### Observações

Este método altera o tamanho e a resolução da imagem de forma semelhante ao recurso "Picture Format -> Compress Pictures" do PowerPoint.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando a resolução não é um valor positivo. |



### Veja Também
* classe [`PictureFillFormat`](/slides/python-net/pt/aspose.slides/picturefillformat)
* enumeração [`PicturesCompression`](/slides/python-net/pt/aspose.slides.export/picturescompression)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)