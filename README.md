# Note Link v0.6.3（ペン/消しゴム/ドラッグ/PDF 安定）
- **ペン/消しゴム**：Pointer Events + Pointer Capture、ResizeObserverで確実にサイズ同期。ツールが Pen/Marker/Eraser のときのみキャンバスが前面＆有効。
- **選択ツール**を追加：付箋/グリッド/PDFブロックの移動は「選択」ツールで行います（描画中に誤タップを防止）。
- **PDF追加**：input の label 連動＋**ドラッグ＆ドロップ**対応（PC）。
- **ブロックのドラッグ**：onPointerDown ベースで**PC/Android**どちらでも移動可能。
- 罫線の「横罫／なし」は継続。グラフ重なりが気になるときは「なし」を選択してください。
