1. 乘号使用 *
除号使用 /

2.从键盘输入：
Scanner hInput = new Scanner(System.in);	// 用于获取键盘输入的对象
hInput.nextXXXX(); // XXXX 表示对应类型

2.Math.pow(x, y) ： 计算 x^y

3.计算优先级：（）高
	* / %    中
        + -       低
4.可以用 () 改变计算的优先级

5.计算三个数字的平均值

6.数据隐含转换：int ---> float ---> double

7.完成 英里(miles) 转变为 公里
static double 定义了一个静态的变量 ---> 它可能会被修改！！！

8.字符串与其他类型数据执行加法运算时，其他数值会转变为字符串，然后两个字符串进行连接。

9.用 System.currentTimeMillis() 函数计算当前的时间（时：分：秒。）

10.1、首先取从起始时间到现在为止，经历的毫秒数 ms
10.2、用毫秒数(ms) 除以 1000，商是到现在为止，经历的总秒数 s
10.3、总秒数（s）除以60，商是到现在为止经历的总分钟数 m，余数是当前时间的秒（当前时间秒）
10.4、总分钟（m）除以60，商是到现在位置经历的总小时数 h，余数是当前时间的分钟（当前时间分钟）
10.5、总小时（h）除以24，商是到现在为止经历的总天数，余数是当前时间的小时（当前时间小时）

11.取余数，也称为模

12.将华氏温度转变为摄氏温度

13.给出下列语句的输出（注意，其中 +、/ 与 = 之间没有空格）
double a = 6.5;
a += a + 1;
System.out.println(a);
int a = 6;
a /= 2;
System.out.println(a);
int a = 6;
int b = a++;
System.out.println(a);
System.out.println(b);
int a = 6;
b = ++a;
System.out.println(a);
System.out.println(b);

b=a++; <==> b =a;   a++;
b=++a; <==> a++;   b=a;

14.计算银行的利息，假设借贷10万元，月利率为 1%，银行采用复利，
借贷三年需要还多少？若每月还贷固定的钱，每月需要还款多少？



