# Curl-Counter
 An AI-based curl counter which will help you to count and see your curl using **media-pipe**


## Angle_Detection

```python
    radians=np.arctan2(c[1]-b[1],c[0]-b[0])-np.arctan2(a[1]-b[1],a[0]-b[0])
    angle=np.abs(radians*180.0/np.pi)
````

**Note** : It won't work on google colab run it on local host jupyter notebook
