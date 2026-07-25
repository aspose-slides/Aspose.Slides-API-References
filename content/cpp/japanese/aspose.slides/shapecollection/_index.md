---
title: ShapeCollection
second_title: Aspose.Slides for C++ APIリファレンス
description: 図形のコレクションを表します。
type: docs
weight: 5110
url: /ja/aspose.slides/shapecollection/
---
## ShapeCollection クラス

シェイプのコレクションを表します。

```cpp
class ShapeCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::GroupShape>>,
                        public Aspose::Slides::IShapeCollection
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameCD](./addaudioframecd/)(**float**, **float**, **float**, **float**) override | 新しい audio フレームを CD トラックにリンクさせて作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameEmbedded](./addaudioframeembedded/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 埋め込み WAV ファイルを持つ新しい audio フレームを作成し、shape collection の末尾に追加します。埋め込みオーディオは [Presentation::get_Audios](../presentation/get_audios/) コレクションに追加されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameEmbedded](./addaudioframeembedded/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 既存の audio オブジェクト（[Presentation::get_Audios](../presentation/get_audios/) リストから）を使用して新しい audio フレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameLinked](./addaudioframelinked/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 外部 audio ファイルにリンクした新しい audio フレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddAutoShape](./addautoshape/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | デフォルトの書式設定で新しい auto shape を作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddAutoShape](./addautoshape/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 新しい auto shape を作成し、shape collection の末尾に追加します。オプションでデフォルトのテンプレート書式設定で初期化できます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [AddChart](./addchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**) override | サンプル系列データと設定で初期化された新しい chart を作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [AddChart](./addchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **bool**) override | サンプル系列データと設定で初期化された新しい chart を作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**, **float**, **float**) override | 指定されたシェイプのコピーを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**) override | 指定されたシェイプのコピーを作成し、shape collection の末尾に追加します。新しいシェイプは *sourceShape* の幅と高さを保持します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 指定されたシェイプのコピーを作成し、shape collection の末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [AddConnector](./addconnector/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | デフォルトテンプレートのスタイリングで新しいコネクタシェイプを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [AddConnector](./addconnector/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 新しいコネクタシェイプを作成し、shape collection の末尾に追加します。オプションでデフォルトテンプレートのスタイリングを適用できます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [AddGroupShape](./addgroupshape/)() override | 空のグループシェイプを新規作成し、shape collection の末尾に追加します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [AddGroupShape](./addgroupshape/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>, **float**, **float**, **float**, **float**) override | 新しいグループシェイプを作成し、指定された SVG 画像を個々のシェイプに変換して、生成されたグループを shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMathShape](./addmathshape/)(**float**, **float**, **float**, **float**) override | 数式コンテンツを保持する新しい矩形 auto shape を作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [AddOleObjectFrame](./addoleobjectframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 新しい OLE オブジェクトフレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [AddOleObjectFrame](./addoleobjectframe/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/), [System::String](../../system/string/)) override | 新しい OLE オブジェクトフレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrame](../ipictureframe/)\> [AddPictureFrame](./addpictureframe/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 指定された画像を含む新しいピクチャーフレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [AddSectionZoomFrame](./addsectionzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 新しい [Section](../section/) Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [AddSectionZoomFrame](./addsectionzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 事前定義された画像を持つ新しい [Section](../section/) Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[SmartArt::ISmartArt](../../aspose.slides.smartart/ismartart/)\> [AddSmartArt](./addsmartart/)(**float**, **float**, **float**, **float**, [SmartArt::SmartArtLayoutType](../../aspose.slides.smartart/smartartlayouttype/)) override | 新しい [SmartArt](../../aspose.slides.smartart/) 図表を作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomFrame](../isummaryzoomframe/)\> [AddSummaryZoomFrame](./addsummaryzoomframe/)(**float**, **float**, **float**, **float**) override | 新しい Summary Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [AddTable](./addtable/)(**float**, **float**, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>) override | 新しいテーブルを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [AddVideoFrame](./addvideoframe/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 新しいビデオフレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [AddVideoFrame](./addvideoframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | 新しいビデオフレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [AddZoomFrame](./addzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 新しい Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [AddZoomFrame](./addzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 新しい Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [iterator](./iterator/) [begin](./begin/)() | コレクションの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | const 修飾されたコレクションインスタンスの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | コレクションの最初の const 修飾要素（存在する場合）を指すイテレータを取得します。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | コレクションの最後の const 修飾要素の直後を指すイテレータを取得します。 |
| void [Clear](./clear/)() override | shape collection からすべてのシェイプを削除します。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>, **int32_t**) override | コレクションのすべての要素を指定された配列にコピーします。 |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | コレクションのすべての要素を指定された配列にコピーします。 |
| [iterator](./iterator/) [end](./end/)() | コレクションの最後の要素の直後を指すイテレータを取得します。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | const 修飾されたコレクションインスタンスの最後の要素の直後を指すイテレータを取得します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスでオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 では NaN はどの値とも等しくないとされるが、C# スタイルで NaN 同士を等しいとみなす浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 では NaN はどの値とも等しくないとされるが、C# スタイルで NaN 同士を等しいとみなす浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部専用です。 |
| **int32_t** [get_Count](./get_count/)() override | コレクションが実際に保持している要素数を取得します。読み取り専用 **int32_t**。 |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | シェイプコレクションの親グループシェイプオブジェクトを取得します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | 同期ルートを返します。読み取り専用 [System::Object](../../system/object/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>\> [GetEnumerator](./getenumerator/)() override | コレクションを列挙するイテレータを返します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [idx_get](./idx_get/)(**int32_t**) override | 指定されたインデックスの要素を取得します。読み取り専用 [IShape](../ishape/)。 |
| **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | コレクション内で指定されたシェイプが最初に出現するゼロベースインデックスを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameCD](./insertaudioframecd/)(**int32_t**, **float**, **float**, **float**, **float**) override | CD トラックにリンクした新しい audio フレームを作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameEmbedded](./insertaudioframeembedded/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 埋め込み WAV ファイルを持つ新しい audio フレームを作成し、指定されたインデックスに挿入します。埋め込みオーディオは [Presentation::get_Audios](../presentation/get_audios/) コレクションに追加されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameEmbedded](./insertaudioframeembedded/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 既存の audio オブジェクト（[Presentation::get_Audios](../presentation/get_audios/) リストから）を使用して新しい audio フレームを作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameLinked](./insertaudioframelinked/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 外部 audio ファイルにリンクした新しい audio フレームを作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [InsertAutoShape](./insertautoshape/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | デフォルトテンプレート書式設定で新しい auto shape を作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [InsertAutoShape](./insertautoshape/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | デフォルトテンプレート書式設定で新しい auto shape を作成し、指定されたインデックスに挿入します。オプションで初期化できます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [InsertChart](./insertchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **int32_t**) override | サンプル系列データと設定で初期化された新しい chart を作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [InsertChart](./insertchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **int32_t**, **bool**) override | サンプル系列データと設定で初期化された新しい chart を作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**, **float**, **float**) override | 指定されたシェイプのコピーを作成し、指定されたインデックスに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**) override | 指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。新しいシェイプは *sourceShape* の幅と高さを保持します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプコレクションに挿入します。クローンされたシェイプは元の位置とサイズを保持します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [InsertConnector](./insertconnector/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 新しいコネクタシェイプを作成し、指定されたインデックスでシェイプコレクションに挿入し、デフォルトのテンプレートスタイルを適用します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [InsertConnector](./insertconnector/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 新しいコネクタシェイプを作成し、指定されたインデックスでシェイプコレクションに挿入し、オプションでデフォルトのテンプレートスタイルを適用します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [InsertGroupShape](./insertgroupshape/)(**int32_t**) override | 新しい空のグループシェイプを作成し、指定されたインデックスでシェイプコレクションに挿入します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [InsertOleObjectFrame](./insertoleobjectframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 新しいOLEオブジェクトフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [InsertOleObjectFrame](./insertoleobjectframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/), [System::String](../../system/string/)) override | 新しいOLEオブジェクトフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrame](../ipictureframe/)\> [InsertPictureFrame](./insertpictureframe/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 指定された画像を含む新しいピクチャーフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [InsertSectionZoomFrame](./insertsectionzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 新しい [Section](../section/) ズームフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [InsertSectionZoomFrame](./insertsectionzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 事前定義された画像を使用した新しい [Section](../section/) ズームフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomFrame](../isummaryzoomframe/)\> [InsertSummaryZoomFrame](./insertsummaryzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**) override | 新しいサマリズームフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [InsertTable](./inserttable/)(**int32_t**, **float**, **float**, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>) override | 新しいテーブルを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [InsertVideoFrame](./insertvideoframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 新しいビデオフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [InsertZoomFrame](./insertzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 新しいズームフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [InsertZoomFrame](./insertzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 事前定義された画像を使用した新しいズームフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子と同等です。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | シーケンスに対してアキュムレータ関数を適用します。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | シーケンスのすべての要素が条件を満たすかどうかを判断します。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | シーケンスに要素が含まれているかどうかを判断します。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | シーケンスの要素が存在するか、または条件を満たすかどうかを判断します。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 数値シーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 入力シーケンスの各要素に変換関数を呼び出して得られる値のシーケンスの平均を計算します。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 要素を指定された型にキャストします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 2 つのシーケンスを連結します。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | シーケンスに指定された値が含まれているかどうかを判断します。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | シーケンスの要素数を返します（直接カウントにより計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの要素数を返します。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | シーケンス内の指定インデックスの要素を返します。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | シーケンス内の指定インデックスの要素を返します。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | シーケンスの最初の要素を返します。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 指定された条件を満たすシーケンスの最初の要素を返します。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | シーケンスの最初の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 条件を満たすシーケンスの最初の要素を返します。該当する要素が見つからない場合はデフォルト値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | シーケンスの要素をグループ化します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | シーケンスの要素をグループ化します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | シーケンスの最後の要素を返します。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | シーケンスの最後の要素を返します。シーケンスが空の場合はデフォルト値を返します。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を呼び出し、得られた最大値を返します。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 汎用シーケンスの各要素に変換関数を呼び出し、得られた最小値を返します。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | シーケンスの要素を指定された型でフィルタリングします。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector で選択されたキー値に基づき、シーケンスの要素を昇順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector で選択されたキー値に基づき、シーケンスの要素を降順にソートします。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | シーケンスの要素順序を逆転させます。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | シーケンスの要素を変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 要素のインデックスを組み込んで、シーケンスの各要素を新しい形に変換します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | シーケンスの各要素を投影し、得られたシーケンスを1つのシーケンスに結合します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素をスキップし、残りを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | シーケンスの先頭から指定された数の連続要素を返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | シーケンスから配列を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | シーケンスから List<T> を作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 指定された述語に基づいてシーケンスをフィルタリングします。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドと同等です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | シェイプコレクションから指定されたシェイプの最初の出現を削除します。 |
| void [RemoveAt](./removeat/)(**int32_t**) override | シェイプコレクションから指定インデックスのシェイプを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | シェイプコレクション内で指定されたシェイプを新しい位置に移動します。 |
| void [Reorder](./reorder/)(**int32_t**, const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>\&) override | シェイプコレクション内で指定されたシェイプを移動し、指定されたインデックスから配置します。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\> [ToArray](./toarray/)() override | すべてのシェイプを含む配列を作成して返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | 指定された範囲のすべてのシェイプを含む配列を作成して返します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドと同等です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | コレクションの const 修飾されたインスタンスの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | コレクションの最初の要素（存在する場合）を指すイテレータを取得します。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | コレクションの const 修飾されたインスタンスの最後の要素（存在する場合）の直後を指すイテレータを取得します。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | コレクションの最後の要素（存在する場合）の直後を指すイテレータを取得します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 型定義

| 型定義 | 説明 |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | 現在のコレクションでイテレータ型として使用されるコレクション型です。 |
| [iterator](./iterator/) | イテレータ型です。 |
| [const_iterator](./const_iterator/) | const イテレータ型です。 |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 仮想化された要素型です。 |
| [virtualized_iterator](./virtualized_iterator/) | 仮想化された型です。 |
## 参照

* クラス [DomObject](../domobject/)
* クラス [IShapeCollection](../ishapecollection/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)