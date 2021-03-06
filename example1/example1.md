# Work with CSV files
## Offer example 1
[Dummy data generator](https://github.com/zhenik-poc/minio-gen-passtry)  

Each 5 seconds `Dummy data generator application` produce `.csv` file with some data to minio bucket (bucket name: `default`). 
File name is random UUID with `.csv` format.   

Data inside file looks like:  
```
id,timestamp,value
666c4dae-2098-4713-8113-016c8ce34cc9,1588064319,8sDr
e5a57e31-3773-4c59-a811-4d8585547470,1588064319,x5LRgxINkOb
82ede752-37ed-4517-b76d-b1d1c3c30e6b,1588064319,CvB
ec16b662-d535-4e92-9d7a-95854a8f75fc,1588064319,8D1FrzfOwf
be1d1d54-afaf-4e80-836a-6486b8ab4810,1588064319,8GLa06NRCOFtIv8s1
4aa4065e-7b3a-478e-b34f-bbfec35f0d08,1588064319,150RQasB72XeavyW5JB
c1beb5c9-9013-4271-b4f3-c0099cfd4032,1588064319,9o9V
e8c96669-9987-44d0-9e39-b8d7880bfe6f,1588064319,CSvSQQhs0uV
```

Minio screenshot
![img](./example_1_minio.png)

Diagram
![img](./diagram_1.png)
### Idea example 1
Show the power `presto` queries.
How to expand:
1. Add dvml2 schema generator for hive-metastore (presto)
2. Add kafka, add notifications, add sctreaming example
