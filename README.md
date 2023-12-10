# Time Series unlearning 

There are steps to complete the task 
1. run_DLinear_unlearning_train.py
   --> This part learn the bigpart of the dataset it uses for unlearning part
2. run_DLinear_unlearning.py
   -->  This part learn the unlearing method,  in parser you should add bigpart train checkpoint to learn!!
3. run_DLinear_unlearning_Delete_smallpart.py
   --> you can learn small part, not use unlearing just make a model small(9 features --> 8 features)

4. run_DLinear_unlearning_test.py
   --> you can test whether bigpart model unlearned well



