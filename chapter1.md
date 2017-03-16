---
title       : Insert the chapter title here
description : Insert the chapter description here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf


--- type:TabExercise lang:r xp:100 skills:1 key:ed98f7522c
## Testing subexercises


*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =type1
NormalExercise

*** =key1: 4029c42036

*** =instructions1
This is the first exercise

*** =solution1
```{r}
print("test")
```

*** =sct1
```{r}
# Some sct
success_msg("Good!")
```

*** =type2
MultipleChoiceExercise

*** =key2: 9db8c33cba

*** =question2
This is the second exercise

*** =options2
- One
- Two
- Three

*** =sct2
```{r}
# Some sct
test_mc(2, feedback_msgs = c("one", "two", "three"))
```