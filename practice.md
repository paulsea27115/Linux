# python
 - 3
   - 4
     - 5
 - 백준 3003번 문제
```python
b = [1,1,2,2,2,8]
a = list(map(int,input().split()))

for i in range(0,len(a)):
  print(b[i]-a[i])
```
github link : <https://github.com/paulsea27115>

# c
```c
#include <stdio.h>

void main(){
  int num;
  scanf_s("%d"&num);
  for(int i = 0; i < num; i++){
    scnaf_s("%d");
  }
  
}

# c++
```c++
#include <iostream>
#include <vector>
#include <algorithm>

using namespce std;

int main(){
  vector<int> v;
  int a,b;
  cin > a;
  for(int i=0; i<a;i++){
    cin >> b;
    v.emplace_back(b);
  }
  sort(v.begin(),v.end());
  for(int i = 0; i <v.size();i++){
    cout << v[i];
  }
  return 0;
}
```

# java

```java
import java.util.*;
import java.lang.*;

class test{
  public static void main(string []args){
    Scanner sc = new Scanner(System.in);
    int random = (int)(Math.random()*10)+1;
    int num;
    while(true){
      System.out.print("input:");
      num = sc.nextInt();
      if(num == random){
        break;
      } else {
        System.out.println("try again");
      }
    }    
    sc.close();
  }
}
```
