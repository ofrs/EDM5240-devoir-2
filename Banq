# coding: utf-8

import json
import csv
import requests



fichier = "banq.csv"

entete = entete = {
	"User-Agent":"Ophélie Farissier",
	"From":"phelie07@hotmail.fr"

}
 

b = 0

for n in range(1000,2001):
b += n 

url = "http://collections.banq.qc.ca/api/service-notice?handle=52327/"

z = str(b)
j = url + k
n = j.strip( )


for n in req :
	
	req = requests.get(url,headers=entete)

	# print(req) 

	

	if "audio" in req :
		infos = []
		
		infos.append(collection["titre"])
		infos.append(collection["createurs"][0])
		infos.append(colection["description"])
		
		infos.append(collection["descriptionMat"])
		infos.append(collection["url"][0])
		
		for collection in dateCreation.values():
			infos.append(collection["dateCreation"])



			print(infos)
			print("~"*80)
			b -= n


		


		f2 = open(fichier,"a")
		banq = csv.writer(f2)
		banq.writerow(infos)
