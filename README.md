# node-jwt-auth

## Register
### {POST} /api/register
### body - firstname lastname email password password2
![image](https://user-images.githubusercontent.com/58978406/100518819-04d9e900-31ba-11eb-98c6-3015fc3782b5.png)


##  Login
### {POST} /api/login
### body - email password
### token will show in cookies
 
![image](https://user-images.githubusercontent.com/58978406/100518864-5f734500-31ba-11eb-828c-1bcae7818732.png)
### Token
![image](https://user-images.githubusercontent.com/58978406/100518936-bf69eb80-31ba-11eb-9de5-f846a746252a.png)


## User profile
### {GET} /api/profile
### show only those which are login if you want to use different login then logout previous one
![image](https://user-images.githubusercontent.com/58978406/100518957-e2949b00-31ba-11eb-8452-1c6e68f21441.png)


## LogOut
### {GET} /api/logout
![image](https://user-images.githubusercontent.com/58978406/100518986-1374d000-31bb-11eb-8ee1-4e06a5a7f51a.png)
