---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions sınıf

Represents options which can be used to manage BLOB handling rules and other BLOB settings.

The BlobManagementOptions type exposes the following members:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides/blobmanagementoptions/__init__/#) | Yeni varsayılan blob yönetim seçenekleri oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/tr/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Bu özellik, Presentation sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya <br/>            veya akışın sahibi olup olamayacağını tanımlar. Örneğin sahibi olması durumunda kaynağı kilitler. Bu, <br/>            BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) <br/>            Presentation örneğinin yaşam süresi boyunca değiştirilemez. |
| [`is_temporary_files_allowed`](/slides/python-net/tr/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde <br/>            azaltır ancak dosya oluşturma izinleri gerektirir.<br/>            Sunumla çalışma tamamlandıktan sonra tüm dosyalar silinecektir. |
| [`temp_files_root_path`](/slides/python-net/tr/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak Sistem geçici dizini kullanılacaktır. <br/>            Barındırma işleminin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/tr/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar<br/>            belleğe yüklenir; bu sınır aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellek içinde tutmak performansı maksimize eder ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)