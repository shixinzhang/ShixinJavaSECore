个人理解主要可以用在程序运行中可以动态调用程序类和方法，知道的设计模式中动态proxy实现就用的inflate实现的， 但是当我们发布releases版本时候一般都进行了代码混淆， 这样反射就不起作用了。

http://a.codekk.com/detail/Android/Mr.Simple/%E5%85%AC%E5%85%B1%E6%8A%80%E6%9C%AF%E7%82%B9%E4%B9%8B%20Java%20%E5%8F%8D%E5%B0%84%20Reflection

http://www.liuling123.com/2013/05/java-reflex.html

http://blog.csdn.net/jiangwei0910410003/article/details/18178687

JAVA反射机制是在运行状态中, 对于任意一个类, 都能够知道这个类的所有属性和方法; 对于任意一个对象, 都能够调用它的任意一个方法和属性; 这种动态获取的信息以及动态调用对象的方法的功能称为java语言的反射机制.

主要作用有三：

运行时取得类的方法和字段的相关信息。

创建某个类的新实例(.newInstance())

取得字段引用直接获取和设置对象字段，无论访问修饰符是什么。

用处如下：

观察或操作应用程序的运行时行为。

调试或测试程序，因为可以直接访问方法、构造函数和成员字段。

通过名字调用不知道的方法并使用该信息来创建对象和调用方法。