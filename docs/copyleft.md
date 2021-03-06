## 什么是 Copyleft? 

>Copyright © 1996–2009, 2013 自由软件基金会。此文最初于发表1996年发表在<http://gnu.org>。

Copyleft 是一种使一个程序或其它工作自由的通用方法，并要求该程序（或其他作品）的所有修改和衍生版本也是自由的。

使一个程序成为自由软件最简单的方法就是将它放到一个不受版权限制的公有领域。如果他们足够明智，就应该允许人们共享该程序和他们的改进成果。但是这也使得那些不愿合作的人有权利将该程序转化为专有软件。他们可以或多或少地做一些修改，并将其作为专有软件发布。而获得修改版程序的人将不能拥有原作者赋予他们的自由，因为中间人已经将其剥夺了。

在 GNU 工程中，我们的目标是赋予*所有*用户重新发布和修改 GNU 软件的自由。如果中间人剥夺了这种自由，即便我们可能会有很多使用者，但他们将不能享有自由。因此我们使它“Copyleft”，来代替将 GNU 软件放到公有领域。Copyleft 指明任何人重新发布软件，不管有没有修改，都必须将这种自由传递到下一个副本中并改变它，以使人们更多的复制和修改。Copyleft 保证了每一位用户都拥有自由。

Copyleft 也对其他程序员发布自由软件提供了一种激励，重要的自由程序如 GNU C++ 编译器就是因为这个原因而存在。

Copyleft 也可以帮助那些想给自由软件做改进的程序员获得自由去改进自由软件。这些程序员通常在那些为了赚更多钱，而几乎什么都干的公司或大学里工作。一个程序员可能想向社区贡献他的改进，但是他的老板可能反而想将其应用到专有软件产品中。

当我们向老板解释不以自由软件形式发布改进版本是非法时，老板常常决定与其将其舍弃不如将其作为自由软件发布。

要让一个程序 Copyleft，我们首先应指出它是有版权的；随后我们附加发布条款，这些条款有法律效力并且赋予每个人使用、修改、重新发布该程序，*或者任何基于该程序的派生程序*的源代码的权利。但前提是这些发布条件没有改变。因此，代码和自由在法律上是不可分割的。

专有软件开发者利用版权来剥夺用户的自由，我们用版权来保证他们的自由。这正是为什么我们颠倒这个名字，将"copyright"（版权）改为"copyleft"。

"Copyleft"是一种对程序享有版权的方式。它不意味着放弃版权；事实上，那样做就不是 copyleft 了。Copyleft 里的单词"left"与动词"to leave"（离开）没什么联系——只是与"right"（右边）反向的一种说法。

Copyleft 是一个抽象的概念，而你不能直接使用抽象的概念；你只能使用该概念的一个具体实现。在 GNU 工程中，为大多数软件所使用的具体发布规则都包含在了 GNU 通用公共许可证（GNU General Public License）中。GNU 通用公共许可证经常被简称为 GNU GPL。还有一个关于GUN GPL 常见问题的页面<http://gnu.org/licenses/gpl-faq.html>，你也可以阅读为什么FSF从贡献者那得到版权转让<http://gnu.org/copyleft/why-assign.html>。

Copyleft 的一种替代形式，是 GNU Affero 通用公共许可证（GNU Affero General Public License，AGPL），主要应用于服务器上的程序。它可以确保公开服务器上的修改版也公开发布源代码。

Copyleft 的另一种替代形式，GNU 宽通用公共许可证（GNU Lesser General Public License，LGPL），应用于一小部分（并非全部）的 GNU 库。想了解更多关于 LGPL 的正确使用，请阅读文章《为什么我们不应该在新的开发库中使用 LGPL》<http://gnu.org/philosophy/why-not-lgpl.html>。

GNU 自由文档许可证 (GNU FDL) 是Copyleft的一种形式，用于在手册、教材或其它文档上以保证任何人都可以自由的复制和发布它们，不管是否对它们进行了修改，也不管是不是进行商业化使用。

相应的许可证被包含在众多手册和每个 GNU 源代码的发布中。

假如你是版权所有人，所有这些设计的许可证能让你很容易的接受并应用于自己的作品中。做这件事你不需要修改许可证，仅仅在作品中包含一份许可证的副本，并且在源文件中添加声明，以示使用了适当的许可证。

对许多不同的程序使用相同的发布条款，使得在不同的程序间复制代码变得很容易。既然都有相同的发布条款, 这就没有必要去考虑这些条款是否相容。LGPL 中有一项规定，它可以允许你把发布条款改成普通的 GPL，因此你可以将代码拷贝到另一个使用 GPL 的程序当中。第三版的 LGPL 被当作了 GPL 第三版的例外，所以自动具有兼容性。

如果你想用 GNU GPL 或 GNU LGPL 来 copyleft 你的程序，请查看许可证介绍页面的建议<http://gnu.org/copyleft/gpl-howto.html>。作为建议，请注意你必须使用我们许可证的全文。每个都是一个不可分割的整体，因此部分复制是不允许的。

如果你用 GNU FDL 来 copyleft 你的手册，请查看 FDL 文本结尾的说明和 GFDL 说明页面<http://gnu.org/copyleft/fdl-howto.html>。同样，部分复制是不允许的。

使用园圈里反转的字母 C 作为版权符号是一个法律错误。Copyleft 是基于合法的版权，所以作品应该有版权声明。版权声明要求要么使用版权符号（园圈里的字母 C），或使用单词“版权”（Copyright）。

园圈里反转的字母 C 没有特别的法律意义，因此它不能成为一个版权声明。也许放在书籍封面、海报上很有趣，但请注意其代表网页时的情况。