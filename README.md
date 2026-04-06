import random

names = ['Aditya','Harshit','Ajay','Ishaan','Virat','Anil','Sahil','Nikhil','Iswar','Aman','Krishna','Mohit','Pranav','Shaurya']

places = ['Mumbai','Kolkata','Bhagyanagar','Vijaywada','Indore','Patna','Ranchi','Kochi','Jalandhar','Delhi','Ludhiana','Bangalore']

body = ['went a grand building and took a photograph','met very famous celebrity','went to the most beautiful spot where he wanted to visit eagerly','collected stamps & old currencies','learnt their traditional dance','celebrated New Year','tasted their local foods']

roles = ['a college student','a youtuber','a vlogger','a school student','a normal guy','a retired army officer','a professor','an LPU verto','an adventurous guy']

weather = ['a very hot and humid day','a cloudy day','a rainy day','a cold night','a sunny day']

word = ['Once upon a time','A long time ago','In earlier times','On 20th January']

saying = ['whose name was','named','known as']

whom = ['to his family.','to his friends.','to his classmates.','to his mother.','to his father.','to his grandparents.']

next_ = ['5 days later','2 days later','3 days later','After 5 days']

gone = [', after office he did not return to his home',', after his work he did not return to his quarter',', he suddenly disappeared on the way between his home & office','after going for shopping he did not come home again']

scene = ['. All his family members started searching him','. His father filed a police complaint','. His friends started worrying about him']

then = ['he somehow called his family','his father received a call from him','he called his friend Rohit']

know = ['they all went to his stated location','they reached that location told by him']

after = ['he talked about the mishap','he explained the whole incident','he described what happened to him']

plot = ['but his friend was involved in drug peddling','but his friend was a drug supplier']

cheated = [', his friend cheated him and mixed drug pills in his soft drink',', his friend suspiciously gave him drug pills by mixing in his drink',', his friend forced him to consume hard drinks heavily']

profit = ['. For his own profit he betrayed his childhood friend','. Greedy for money he cheated his best friend','. To reach his sales target he betrayed his friend']

case = ['. This whole scenario was reported to higher officials','. This whole scenario was reported to police']

accused = ['and they assured the victim that the accused would not be spared','and they confirmed the culprit would be punished']

news = ['. This news was covered on television','. This news was covered in newspapers']

solve = ['. Later this case was solved with the help of special cops']

end = ['. From this story we learn that good experiences can turn into bad ones']

learnings = [', and we should never blindly trust anyone']

# FIX: each assignment on separate line
randomname = random.choice(names)
randomplace = random.choice(places)
randombody = random.choice(body)
randomrole = random.choice(roles)
randomweather = random.choice(weather)
randomword = random.choice(word)
randomsaying = random.choice(saying)
randomwhom = random.choice(whom)
randomnext = random.choice(next_)
randomgone = random.choice(gone)
randomscene = random.choice(scene)
randomthen = random.choice(then)
randomknow = random.choice(know)
randomafter = random.choice(after)
randomplot = random.choice(plot)
randomcheated = random.choice(cheated)
randomprofit = random.choice(profit)
randomcase = random.choice(case)
randomaccused = random.choice(accused)
randomnews = random.choice(news)
randomsolve = random.choice(solve)
randomend = random.choice(end)
randomlearnings = random.choice(learnings)

# FIX: proper concatenation and spacing
story = (
    randomword + " " + randomrole + " " + randomsaying + " " + randomname +
    " travelled to a beautiful city called " + randomplace +
    " where it was " + randomweather +
    " and there he " + randombody +
    ". After that he shared his experiences " + randomwhom + " " +
    randomnext + " " + randomgone + randomscene + " " +
    randomthen + ", " + randomknow + ", " + randomafter + " " +
    randomplot + randomcheated + randomprofit + randomcase + " " +
    randomaccused + randomnews + randomsolve + randomend + randomlearnings
)

print(story)
