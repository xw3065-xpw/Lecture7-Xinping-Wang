lecture7 assisgnment what I changed: 
I want every trials have changing colors for both dots and the fixation cross so
- I randomized color to each trial between RGB range -0.5 to 0.7 (I like these colors):
  ```python
  shared_color = [random.uniform(-0.5,0.7) for _ in range(3)]

- And then I made the dots and the fixation cross colors consistent:
  ```python
  fix.color = shared_color
  dots.color = shared_color
