---
title: File
second_title: Referência da API Aspose.Slides para C++
description: Fornece métodos para manipular arquivos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 261
url: /pt/system.io/file/
---
## File classe

Fornece métodos para manipular arquivos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class File
```

## Métodos

| Método | Descrição |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Anexa strings da coleção de strings especificada ao arquivo especificado usando a codificação especificada, escrevendo cada string em uma nova linha. Se o arquivo especificado não existir, ele será criado. O arquivo é fechado após a gravação de todas as strings. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Anexa a string especificada ao arquivo especificado usando a codificação especificada. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Cria um objeto [StreamWriter](../streamwriter/) que anexa texto ao arquivo especificado usando codificação UTF-8. Se o arquivo especificado não existir, ele será criado. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Copia o arquivo especificado para o local especificado. Se o arquivo de destino já existir, um parâmetro especifica se ele deve ser sobrescrito. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Cria um novo arquivo (ou sobrescreve o existente) e o abre para acesso de leitura e gravação usando o tamanho de buffer e as opções especificados. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Cria um novo ou abre um arquivo existente para gravação de texto codificado em UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Exclui o arquivo ou diretório especificado. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determina se o caminho especificado referencia um arquivo existente. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Retorna os atributos da entidade especificada. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Retorna a hora de criação da entidade especificada como hora local. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Retorna a hora de criação da entidade especificada como hora UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Retorna a hora de último acesso da entidade especificada como hora local. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Retorna a hora de último acesso da entidade especificada como hora UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Retorna a hora da última gravação da entidade especificada como hora local. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Retorna a hora da última gravação da entidade especificada como hora UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Move o arquivo especificado para o novo local. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Abre o arquivo especificado no modo especificado para leitura e gravação sem compartilhamento. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Abre o arquivo especificado no modo especificado, com o tipo de acesso e a opção de compartilhamento especificados. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Abre o arquivo especificado apenas para leitura, no modo 'Open' com acesso compartilhado para leitura. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Abre o arquivo existente especificado para leitura de texto usando codificação UTF-8 sem compartilhamento. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Abre o arquivo especificado apenas para gravação, no modo 'OpenOrCreate' sem compartilhamento. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Lê o conteúdo do arquivo binário especificado para um array de bytes. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lê o conteúdo do arquivo de texto especificado linha a linha para um vetor de strings usando a codificação de caracteres especificada. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lê o conteúdo do arquivo de texto especificado para um único objeto [String](../../system/string/) usando a codificação de caracteres especificada. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lê o conteúdo do arquivo de texto especificado linha a linha usando a codificação de caracteres especificada e retorna uma coleção enumerável de strings, cada uma representando uma única linha do conteúdo do arquivo. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Substitui o conteúdo de um arquivo por outro e cria um backup do arquivo substituído. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Define os atributos especificados no arquivo especificado. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define a hora da última gravação da entidade especificada como hora local. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define a hora da última gravação da entidade especificada como hora UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Sobrescreve o arquivo binário especificado e escreve os bytes especificados nele. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Cria um novo arquivo de texto ou sobrescreve o existente e grava todas as strings da coleção enumerável de strings especificada nele, cada string em uma nova linha, usando a codificação especificada. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Cria um novo arquivo de texto ou sobrescreve o existente e grava todas as strings do array de strings especificado nele, cada string em uma nova linha, usando a codificação especificada. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Cria um novo arquivo de texto ou sobrescreve o existente e grava o conteúdo da string especificada nele usando a codificação especificada. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Valor padrão do número de bytes armazenados em buffer durante a leitura e gravação de um arquivo. |

## Ver também

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)