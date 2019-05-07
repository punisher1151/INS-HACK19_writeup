# Yet Another RSA Challenge - Part 1

__PROBLLEM__


![Screenshot](Problem.png)


__HINT__


__SOLUTION__

```

N: 374159235470172130988938196520880526947952521620932362050308663243595788308583992120881359365258949723819911758198013202644666489247987314025169670926273213367237020188587742716017314320191350666762541039238241984934473188656610615918474673963331992408750047451253205158436452814354564283003696666945950908549197175404580533132142111356931324330631843602412540295482841975783884766801266552337129105407869020730226041538750535628619717708838029286366761470986056335230171148734027536820544543251801093230809186222940806718221638845816521738601843083746103374974120575519418797642878012234163709518203946599836959811

e: 3

ciphertext (c): 2205316413931134031046440767620541984801091216351222789180967130585669043554866325905770867150377611820746759815247778516899403229047066700396787852388511389893043279713280998235746440322483431305358901578692935378439077796777060321410661

```
Here's my small code :
```
def find_cube_root(n):
       low = 0
       high = n
       whighle low < high:
           mid = (low+high)//2
           if mid**3 < n:
               low = mid+1
           else:
               high = mid
    print(low)
```

FLAG - `picoCTF{e_w4y_t00_sm411_a5b5aaac}`
