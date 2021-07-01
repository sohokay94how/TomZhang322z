# GooFlow 

> This is an online process designer component used to build flowcharts on the WEB side. Various flow charts, logic flow diagrams, data flow diagrams, or functional implementations of processes that need to go through the process can be designed. The excellent user experience makes the interface easy to use, no matter the driver or the user can easily use. And compatible with mainstream browsers (ie9--ie edge, chrome, firefox).

<p>GooFlow has been converted to a closed source project, and clones and downloads are no longer available on github. For the trial version, please visit the[Repository Homepage](https://gitee.com/gooflow/gooflow)</p>


## Authorization note: ##
GooFlow has been converted to a closed source project. The version currently on the hosted page is only a trial version. It will make the CPU meaningless and idling, and it will contain timed pop-up ads. It can only be used for local function testing. In use; 
if it is to be applied to a software development project, it can only be used without any additional official version, and you need to contact the author to purchase the license. Thank you. (Whether the official version or the trial version, if you evade the purchase authorization and use it directly for the project, stealing it for profit is a serious infringement, and it is no different from the theft. The responsibility for any consequences arising from the infringer is at your own risk. Please only The party that wants to eat rice for free is fully aware of the responsibility of the author and his own company and customers.) <br>
Contact:<br>
WeChat: 18648945414<br>
QQ: 115247126<br>
E-mail: fool-egg@163.com <br>
Authorized price: Js native edition is <b>￥4,700RMB/product</b> ，Vue/React edition is <b>￥5,400RMB/product</b> 。<br>

More details are subject to the official website:：[https://gooflow.xyz](https://gooflow.xyz)

## features ##
* 跨领域:流程图设计器不止用在电信领域,在其它需要IT进行技术支持的领域中都有重大作用.
* 页面顶部栏、左边侧边栏均可自定义；
* 当左边的侧边栏设为不显示时，为只读状态，此时的视图区可当作是一个查看器而非编辑器。
* 当前最新版本已全部使用自定义的阿里巴巴矢量图标库，可不再需要一张用来显示图标样式的图片。
* 侧边工具栏除了基本和一些流程节点按钮外，还自定义新的节点按钮，自定义节点都可以有自有的图标、类型名称，定义后在使用可可在工作区内增加这些自定义节点。
* 顶部栏可显示流程图数据组的标题，也可提供一些常用操作按钮。
* 顶部栏的按钮，除了撤销、重做按钮外，其余按钮均可自定义点击事件。
* 可画直线、折线；折线还可以左右/上下移动其中段。
* 具有区域划分功能，能让用户更直观地了解哪些节点及其相互间的转换，是属于何种自定义区域内的。
* 具有标注功能，用橙红色标注某个结点或者转换线，一般用在展示流程进度时。
* 能直接双击结点、连线、分组区域中的文字进行编辑
* 在对结点、连线、分组区域的各种编辑操作，如新增/删除/修改名称/重设样式或大小/移动/标注时，均可捕捉到事件，并触发自定义事件，如果自定义事件执行的方法返回FALSE，则会阻止操作。
* 具有操作事务序列控制功能，在工作区内的各种有效操作都能记录到一个栈中，然后可以进行撤销（undo()）或重做（redo()），像典型的C/S软件一样。
* 能将流程图以png图片的格式导出并下载（纯JS实现，但不支持IE9及以下浏览器）

![Preview Image](https://git.oschina.net/uploads/images/2017/0531/145320_f0bb8c2c_472359.png "效果预览图")
<br><br>

## Detail usage: ##
* [Js native edition API documentation](https://gooflow.xyz/docs) 
* [Vue edition API documentation](https://gooflow.xyz/vueDoc)
* [React edition API documentation](https://gooflow.xyz/reactDoc)

## Related example link ##
* Js native edition of the example display (only rely on the last version of jQuery): [click to enter](https://gooflow.xyz/#demo)<br>
* Vue edition of the show: [click to enter](https://gooflow.gitee.io/vue/#)<br>
* React edition of the show: [click to enter](https://gooflow.gitee.io/react/)<br>

*Updated History :**
- **1.4 for All :** <br> Fixed some bugs, optimizing directory structure; Optimize the operation experience. When moving a swimming lane, you can set whether the nodes/lines in the lane follow the movement.
- **1.4, 1.2 for Vue/React :** <br> Important update! The polyline can support 5 polyline segments; optimize multi-selection operation experience, remove single/multiple selection switching; optimize node drag operation experience.
- **1.3.12 :** <br> Important update! Getting rid of the dependency on Jquery and removing the Ajax method implemented through Jquery, IE8 is no longer supported.
- **1.1.0 for Vue/React :** <br> Important update! Increase support for adding block elements by dragging and dropping like Visio.
- **1.3.11 :** <br> Important update! Increase support for adding block elements by dragging and dropping like Visio.
- **1.0.0 for React :** <br> New React Component Edition Reloading Attacks! 
- **1.0.0 for Vue :** <br> New Vue Component Edition Reloading Attacks! 
- **1.3.10 :** <br> Automatically aligns and displays the ability to align guides when moving a block element.
- **1.3.9 :** <br> Important update! Add thumbnail navigation map features, including drag positioning and live scrolling. Add the mouse wheel +Ctrl key to control the zoom function of drawing area.
- **1.3.9r1 :** <br> Important updates! Fixed some newly discovered bugs; increased support for segments, modified the way of setting for the dashed line; added multi-selection features (for nodes and connections only), and enabled bulk move and deletion of multi-selected collections of elements.
- **1.3.8rp :** <br> Fixed some newly discovered bugs and improve the overall operating efficiency; use the new anti-infringement mechanism to replace the original JS mining on the trial version; separate the swimlane support from the core file and form a separate extension function block <code>GooFlow.group.min.js</code>; add note elements (via new function blocks); add custom background image type nodes to adapt to more scenes.
- **1.3.7 :** <br> Minor and Small Bonus: Fixed a small BUG of the actual width and height algorithm of the calculation flow chart. When initializing, the property of setting the initial default name prefix of the node and the lane is added.
- **1.3.6 :** <br> Enhanced functionality! Fixed the problem that the focus event is triggered twice when a element is selected. Adds the right-clicking the blank area of the drawing area to trigger the operation of the blur event. Adds an interface to set the extended service attribute of an element. After the flowchart loaded, user can use two new interfaces to modify the color or text color of an element.
- **1.3.5 :** <br> Feature Update! Grouped lanes have added "milk" color; users can customize special graphics colors and text colors for individual nodes or lines; the designer adds <code>ctrl+c</code> keyword command to copy node and <code>ctrl+v</code> keyword command to paste node.
- **1.3.4 :** <br> Important updates! Fixed some bugs in event response, image export, and drawing area scaling; added four special shape nodes: ellipse, rhombus, parallelogram, and capsule.
- **1.3.3 :** <br> Important functions on line! New support for flowchart data of XML format under Bpmn2.0 specification is added, which can load or export XML data of Bpmn2.0 specification. Allowed users download flowchart data as a json file or Bpmn2.0's XML file. Further optimize the code.
- **1.3.2 :** <br> Optimized the code structure and user experience; Strengthen cohesion, simplify the internal implementation of the process save as picture function and print function, got rid of the dependence on third-party plugins from version 1.1 to 1.2, and exports results more clearly. And could be backwards compatible to IE9; each part of the button could be configured through the built-in interface method; node data added "areaId" optional attribute: indicates which area group (lane) it belongs to. The overall also added support for amd, cmd development model specification.
- **1.3 :** <br> Fixed some bugs that affect the user experience and usage, and add flexible annotation configuration functions for all operation buttons in the workspace.
- **1.2.1 :** <br> Improved support for IE8; optimize the accuracy of manually resized elements; add functionality to print previews or save as PDFs.
- **1.2 :** <br> Major update version! Added method for right-click events and double-click events for nodes, connections, and lane blocks (return false to prevent browser default events from occurring); Add dashed line drawing function method: should be requested by many users Added important flowchart zoom function interface! The scalable range is from 50% to 400% of the original size. (Only provide method interface, you can chooses to bind the third-party's operation element)
- **>1.1 :** <br> BUG has been further amended; the function of exporting the flow chart in the work area into a picture and allowing the user to download has been added. Currently only IE10, IE edge, Chrome, FireFox, Safari browsers can be supported, and this function needs to load new GooFlow.export.min.js extension package.
- **1.0.2 :** <br> Fixed the problem that when a node was originally marked, the marked red mode disappeared after the selection and cancellation.
- **1.0 :** <br> The initial official version. Compared with the previous trial version, the BUG has been further revised, more customizable color items are available, and there is no longer a single picture. All icons are evenly shaped as vector fonts.