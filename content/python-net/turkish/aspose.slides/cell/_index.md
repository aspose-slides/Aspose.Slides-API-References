---
title: Cell class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/cell/
---
## Cell sınıfı

Bir tablonun hücresini temsil eder.

Cell türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/tr/aspose.slides/cell/offset_x/) | Bir tablonun sol kenarından hücrenin sol kenarına olan mesafeyi döndürür.<br/>            Salt Okunur **float**. |
| [`offset_y`](/slides/python-net/tr/aspose.slides/cell/offset_y/) | Bir tablonun üst kenarından hücrenin üst kenarına olan mesafeyi döndürür.<br/>            Salt Okunur **float**. |
| [`first_row_index`](/slides/python-net/tr/aspose.slides/cell/first_row_index/) | Hücre tarafından kapsanan ilk satırın dizinini döndürür.<br/>            Salt Okunur **int**. |
| [`first_column_index`](/slides/python-net/tr/aspose.slides/cell/first_column_index/) | Hücre tarafından kapsanan ilk sütunun dizinini döndürür.<br/>            Salt Okunur **int**. |
| [`width`](/slides/python-net/tr/aspose.slides/cell/width/) | Hücrenin genişliğini döndürür.<br/>            Salt Okunur **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/cell/height/) | Hücrenin yüksekliğini döndürür.<br/>            Salt Okunur **float**. |
| [`minimal_height`](/slides/python-net/tr/aspose.slides/cell/minimal_height/) | Bir hücrenin minimum yüksekliğini döndürür.<br/>            Bu, hücre tarafından kapsanan tüm satırların minimum yüksekliklerinin toplamıdır.<br/>            Salt Okunur **float**. |
| [`margin_left`](/slides/python-net/tr/aspose.slides/cell/margin_left/) | Sol kenar boşluğunu bir TextFrame içinde döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`margin_right`](/slides/python-net/tr/aspose.slides/cell/margin_right/) | Sağ kenar boşluğunu bir TextFrame içinde döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`margin_top`](/slides/python-net/tr/aspose.slides/cell/margin_top/) | Üst kenar boşluğunu bir TextFrame içinde döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`margin_bottom`](/slides/python-net/tr/aspose.slides/cell/margin_bottom/) | Alt kenar boşluğunu bir TextFrame içinde döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`text_vertical_type`](/slides/python-net/tr/aspose.slides/cell/text_vertical_type/) | Dikey metin tipini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`TextVerticalType`](/slides/python-net/tr/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/tr/aspose.slides/cell/text_anchor_type/) | Metin bağlama tipini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`TextAnchorType`](/slides/python-net/tr/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/tr/aspose.slides/cell/anchor_center/) | Bir metin kutusunun hücre içinde ortalanıp ortalanmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`first_row`](/slides/python-net/tr/aspose.slides/cell/first_row/) | Hücrenin ilk satırını alır.<br/>            Salt Okunur [`IRow`](/slides/python-net/tr/aspose.slides/irow). |
| [`first_column`](/slides/python-net/tr/aspose.slides/cell/first_column/) | Hücrenin ilk sütununu alır.<br/>            Salt Okunur [`IColumn`](/slides/python-net/tr/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/tr/aspose.slides/cell/col_span/) | Geçerli hücre tarafından kapsanacak olan üst tabloyun tablo ızgarasındaki ızgara sütun sayısını döndürür. Bu özellik, hücrelerin tabloda diğer hücrelerin dikey sınırlarını kapsayarak birleştirilmiş gibi görünmesini sağlar.<br/>            Salt Okunur **int**. |
| [`row_span`](/slides/python-net/tr/aspose.slides/cell/row_span/) | Birleştirilmiş bir hücrenin kapsadığı satır sayısını döndürür. Bu, diğer hücrelerdeki vMerge özniteliğiyle birlikte kullanılarak yatay birleştirmenin başlangıç hücresini belirtmek için kullanılır.<br/>            Salt Okunur **int**. |
| [`text_frame`](/slides/python-net/tr/aspose.slides/cell/text_frame/) | Bir hücrenin metin çerçevesini döndürür.<br/>            Salt Okunur [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`table`](/slides/python-net/tr/aspose.slides/cell/table/) | Bir hücrenin üst Table nesnesini döndürür.<br/>            Salt Okunur [`ITable`](/slides/python-net/tr/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/tr/aspose.slides/cell/is_merged_cell/) | Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse true, aksi takdirde false döndürür.<br/>            Salt Okunur **bool**. |
| [`cell_format`](/slides/python-net/tr/aspose.slides/cell/cell_format/) | Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür.<br/>            Salt Okunur [`ICellFormat`](/slides/python-net/tr/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/tr/aspose.slides/cell/slide/) | Bir hücrenin üst slaytını döndürür.<br/>            Salt Okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/cell/presentation/) | Bir hücrenin üst sunumunu döndürür.<br/>            Salt Okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |

## Yöntemler

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/tr/aspose.slides/cell/split_by_col_span/#int) | Hücreyi sütun indeksine göre iki hücreye böler. |
| [`split_by_row_span(self, index)`](/slides/python-net/tr/aspose.slides/cell/split_by_row_span/#int) | Hücreyi satır indeksine göre iki hücreye böler. |
| [`split_by_height(self, height)`](/slides/python-net/tr/aspose.slides/cell/split_by_height/#float) | Hücreyi yüksekliğine göre böler. |
| [`split_by_width(self, width)`](/slides/python-net/tr/aspose.slides/cell/split_by_width/#float) | Hücreyi genişliğine göre böler. |


### İlgili
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)