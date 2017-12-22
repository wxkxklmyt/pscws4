# 基于PSCWS4的中文分词工具
词库官方网址：http://www.xunsearch.com/scws/<br>
这是用纯 PHP 代码实现的 C 版 Libscws 的全部功能，即第四版的 PSCWS<br>
PSCWS4 使用文档：http://www.xunsearch.com/scws/docs.php#pscws4<br>
<hr>
<h3>安装</h3>
<pre>composer require wxkxklmyt/pscws4</pre>
<hr>
<h3>使用</h3>
<pre>
/**
 * SCWS中文分词
 *
 * @param string $text 分词字符串
 * @param number $number 权重高的词数量(默认5个)
 * @param string $type 返回类型,默认字符串
 * @param string $delimiter 分隔符
 * @return string|array 字符串|数组
 */
$scws = new Scws();
$scws -> scws('能做到柔和、善解、忍辱，才有办法与人结好缘。——证严法师《静思语》', 5, false);
</pre>
<hr>
官网(我的梦)：https://www.4ui.cn/
<hr>
<p><strong>版权申明：这里只是把PSCWS4封装成composer包，词库版权属于原作者</strong></p>
