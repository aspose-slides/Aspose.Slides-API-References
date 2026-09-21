---
title: IShapeCollection class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/
---
## IShapeCollection 類別

表示一個形狀集合。

IShapeCollection 型別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/parent_group/) | 取得形狀集合的父群組形狀物件。<br/>            唯讀 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。 |

取得指定索引處的元素。  
            唯讀 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | 建立一個新圖表，以範例序列資料和設定進行初始化，並將它<br/>            加入形狀集合的末端。 |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | 建立一個新圖表，以範例序列資料和設定進行初始化，並將它<br/>            加入形狀集合的末端。 |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | 建立一個新圖表，以範例序列資料和設定進行初始化，<br/>            並將它插入形狀集合的指定索引處。 |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | 建立一個新圖表，以範例序列資料和設定進行初始化，<br/>            並將它插入形狀集合的指定索引處。 |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | 建立一個新的 OLE 物件框架，並將它加入形狀集合的末端。 |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | 建立一個新的 OLE 物件框架，並將它加入形狀集合的末端。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | 建立一個新的 OLE 物件框架，並將它插入形狀集合的指定索引處。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | 建立一個新的 OLE 物件框架，並將它插入形狀集合的指定索引處。 |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | 建立一個新的 Zoom 框架，並將它加入形狀集合的末端。 |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | 建立一個新的 Zoom 框架，並將它加入形狀集合的末端。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | 建立一個新的 Zoom 框架，並將它插入形狀集合的指定索引處。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | 建立一個帶有預定義圖像的新 Zoom 框架，並將它插入形狀集合<br/>            的指定索引處。 |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | 建立一個新的 Section Zoom 框架，並將它加入形狀集合的末端。 |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | 建立一個帶有預定義圖像的 Section Zoom 框架，並將它加入形狀集合的<br/>            末端。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | 建立一個新的 Section Zoom 框架，並將它插入形狀集合的<br/>            指定索引處。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | 建立一個帶有預定義圖像的 Section Zoom 框架，並將它插入形狀集合的<br/>            指定索引處。 |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | 建立一個新的視頻框架，並將它加入形狀集合的末端。 |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | 建立一個新的視頻框架，並將它加入形狀集合的末端。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | 建立一個嵌入 WAV 檔案的新音訊框架，並將它加入形狀集合的<br/>            末端。嵌入的音訊會加入 Presentation.Audios 集合。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | 建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將它加入形狀集合的<br/>            末端。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | 建立一個嵌入 WAV 檔案的新音訊框架，並將它插入形狀<br/>            集合的指定索引處。嵌入的音訊會加入 Presentation.Audios<br/>            集合。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | 建立一個新音訊框架，並將它插入形狀集合的指定索引處<br/>            使用 Presentation.Audios 清單中的現有音訊物件。 |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/to_array/#) | 建立並回傳一個包含所有形狀的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/to_array/#int-int) | 建立並回傳一個包含指定範圍內所有形狀的陣列。 |
| [`reorder(self, index, shape)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/reorder/#int-ishape) | 將指定的形狀移動到形狀集合中的新位置。 |
| [`reorder(self, index, shapes)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/reorder/#int-listishape) | 將指定的形狀在形狀集合中移動，從給定的索引開始放置它們。 |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | 建立一個具有預設格式的新自動圖形，並將它加入形狀集合的<br/>            末端。 |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | 建立一個新自動圖形，並將它加入形狀集合的末端，<br/>            可選擇以預設範本格式進行初始化。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | 建立一個新自動圖形，並將它插入形狀集合的指定索引處，<br/>            套用預設範本格式。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | 建立一個新自動圖形，並將它插入形狀集合的指定索引處，<br/>            可選擇以預設範本樣式進行初始化。 |
| [`add_group_shape(self)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_group_shape/#) | 建立一個新的空白群組形狀，並將它加入形狀集合的末端。<br/>            群組的框架會自動調整以適應任何加入的形狀。 |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | 建立一個新群組形狀，將指定的 SVG 圖像轉換為個別形狀，<br/>            並將產生的群組加入形狀集合的末端。 |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | 建立一個具有預設範本樣式的新連接線形狀，並將它加入形狀集合的<br/>            末端。 |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | 建立一個新連接線形狀，並將它加入形狀集合的末端，<br/>            可選擇套用預設範本樣式。 |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | 建立一個新連接線形狀，並將它插入形狀集合的指定索引處，<br/>            套用預設範本樣式。 |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | 建立一個新連接線形狀，並將它插入形狀集合的指定索引處，<br/>            可選擇套用預設範本樣式。 |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | 建立指定形狀的副本，並將它加入形狀集合的末端。 |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | 建立指定形狀的副本，並將它加入形狀集合的末端。<br/>            新形狀保留 `source_shape` 的寬度與高度。 |
| [`add_clone(self, source_shape)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_clone/#ishape) | 建立指定形狀的副本，並將它加入形狀集合的末端。<br/>            複製的形狀保留原始的位置信息與大小。 |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | 建立指定形狀的副本，並將它插入形狀集合的指定索引處。 |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | 建立指定形狀的副本，並將它插入形狀集合的指定索引處。<br/>            新形狀保留 `source_shape` 的寬度與高度。 |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_clone/#int-ishape) | 建立指定形狀的副本，並將它插入形狀集合的指定索引處。<br/>            複製的形狀保留原始的位置信息與大小。 |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | 建立一個 SmartArt 圖表，並將它加入形狀集合的末端。 |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | 建立一個新的 Summary Zoom 框架，並將它加入形狀集合的末端。 |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | 建立一個新的 Summary Zoom 框架，並將它插入形狀集合的指定索引處。 |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | 建立一個新的視頻框架，並將它插入形狀集合的指定索引處。 |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | 建立一個連結至 CD 軌道的新音訊框架，並將它加入形狀集合的末端。 |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | 建立一個連結至 CD 軌道的新音訊框架，並將它插入形狀集合<br/>            的指定索引處。 |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | 建立一個連結至外部音訊檔案的新音訊框架，並將它加入形狀集合的<br/>            末端。 |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | 建立一個連結至外部音訊檔案的新音訊框架，並將它插入形狀<br/>            集合的指定索引處。 |
| [`index_of(self, shape)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/index_of/#ishape) | 回傳集合中指定形狀第一次出現的零基索引。 |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | 建立一個新的矩形自動圖形以容納數學內容，並將它加入形狀集合的<br/>            末端。 |
| [`insert_group_shape(self, index)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_group_shape/#int) | 建立一個新的空白群組形狀，並將它插入形狀集合的指定索引處。<br/>            群組的框架會自動調整以適應任何加入的形狀。 |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | 建立一個包含指定圖像的圖片框架，並將它加入形狀集合的<br/>            末端。 |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | 建立一個包含指定圖像的圖片框架，並將它插入形狀<br/>            集合的指定索引處。 |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | 建立一個新表格，並將它加入形狀集合的末端。 |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | 建立一個新表格，並將它插入形狀集合的指定索引處。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/remove_at/#int) | 從形狀集合中移除指定索引處的形狀。 |
| [`remove(self, shape)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/remove/#ishape) | 從形狀集合中移除指定形狀的第一次出現。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/ishapecollection/clear/#) | 從形狀集合中移除所有形狀。 |

### 參見
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)