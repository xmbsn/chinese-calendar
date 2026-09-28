# 中国日历

一个无需构建步骤的中文日历页面，支持公历月历、农历、每日宜忌、节假日与调休标记。

## 使用

下载项目文件后，直接用现代浏览器打开 `index.html` 即可。节假日和调休安排会按年份在线获取；数据源暂不可用时，页面会显示状态提示。农历与黄历计算由项目内的 `lunar.js` 完成本地计算。

## 功能

- 按年月浏览日期，支持上月、下月和返回今天
- 设置周日或周一为每周起始日
- 显示农历日期、节日、每日宜忌
- 从在线数据源获取法定假日与调休工作日，并提供备用数据源
- 适配窄屏设备

## 数据来源

- 黄历与农历计算：[6tail/lunar-javascript](https://github.com/6tail/lunar-javascript)，许可见 [LICENSE-lunar-javascript.txt](LICENSE-lunar-javascript.txt)
- 节假日安排： [Timor 节假日 API](https://timor.cn/api/holiday/)，以及 [cg-zhou/holiday-calendar](https://github.com/cg-zhou/holiday-calendar) 的 JSON 数据

节假日接口只在数据源提供对应年份安排时显示调休日期；尚未发布或暂不可访问时不会预填日期。
