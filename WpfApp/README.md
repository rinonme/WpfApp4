# WPF小作家

## 2026/11/11

1. 新增一個DocumentViewer視窗，用來顯示和瀏覽文檔內容。
2. 在主視窗MainWindow中新增一個按鈕，點擊後可以打開DocumentViewer視窗。
3. 在DocumentViewer視窗中新增一個RichTextBo內容，並且可以進行編輯。
4. 使用CommandBinding來實現RichTextBox的基本編輯功能，例如複製、剪下、貼上等。
5. 在EditingToolBar中新增文字格式的按鈕，包含加粗、斜體、下劃線、字體顏色等功能。
6. 使用第三方元件ColorPicker來實現字體顏色的選擇功能。
7. 新增變更文字字型的ComboBox，讓使用者可以選擇不同的字型。
8. 新增變更文字大小的ComboBox，讓使用者可以選擇不同的字體大小。

## 2026/11/18

1. 在 MyDocumentViewer.xaml 中，新增按鈕命令綁定，更新字體選擇與顏色選擇的事件處理程序。
2. 在 MyDocumentViewer.xaml.cs 中，實現打開與保存 .rtf 文件的功能，並新增字體顏色、字體家族、字體大小的選擇與初始化邏輯。
3. 更新工具欄按鈕狀態同步邏輯，並新增清空文檔功能。
4. 更新 README.md，補充新增功能的描述。
