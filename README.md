# 字幕工坊 vtools

字幕工坊是一款 Windows 离线视频字幕生成和编辑工具。

## 基础版

基础版提供：

- 视频导入与播放
- 字幕文件加载、编辑、插入、删除与导出
- 中文字幕时间轴同步
- 离线识别模块下载管理

基础版不内置 Whisper 模型。启动程序后，打开“设置 -> 离线识别模块”，可选择下载安装：

- 快速版：速度优先
- 标准版：速度和准确度平衡，推荐
- 完整版：包含多个模型

## 下载

请在仓库的 `artifacts` 目录或 Release 页面下载最新的 `vtools-base-windows-x64.zip`，并可使用 `SHA256SUMS.txt` 校验文件完整性。

- Gitee: <https://gitee.com/xzon/vtools-release/releases>
- GitHub: <https://github.com/wmousew/vtools-release/releases>

解压后运行 `vtools.exe`。

## 系统要求

- Windows 10/11 x64
- 建议至少 8 GB 内存

## 隐私

视频、音频和字幕识别全程在本机处理。程序仅在用户主动下载安装离线识别模块时访问下载服务器。
