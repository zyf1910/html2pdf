<!--
 * @Author: your name
 * @Date: 2022-01-13 21:55:45
 * @LastEditTime: 2022-01-13 22:05:18
 * @LastEditors: your name
 * @Description: 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
 * @FilePath: /html2pdf/README.md
-->
# html2pdf

```
npm install html2pdf-dbs --save
```
```
import html2pdf from "html2pdf-dbs"
``````

```
Vue.use(html2pdf)
``````
```
<Button type="primary" @click="htmlToPdf('domID', 'fileName')">下载</Button>
``````