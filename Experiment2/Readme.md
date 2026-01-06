## Experiment 2b
## MAIN METHOD
```java
class OverloadExample{
    int add(int a, int b){
        return a + b;
    }
    double add(double a, double b){
        return a + b;
    }
    int add(int a, int b, int c){
        return a + b + c;
    }
    public static void main(String[] args) {

        OverloadExample obj = new OverloadExample();

        int result1 = obj.add(10, 20);
        double result2 = obj.add(5.5, 6.6);
        int result3 = obj.add(10, 20, 30);

        System.out.println("sum of two integers= " + result1);
        System.out.println("sum of two double values= " + result2);
        System.out.println("sum of three integers: " + result3);
    }
}

```
##output:



![Output](Experiment2/Experiment2/Overloading.png)
