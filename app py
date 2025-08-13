import numpy as np
import matplotlib.pyplot as plt
dados = np.loadtxt('apples_ts.csv', delimiter=',', usecols=np.arange(1,88, 1))

dados_transpostos = dados.T

print(dados_transpostos)
print(dados_transpostos.size)

datas = dados_transpostos[:,0]
precos = dados_transpostos[:,1:6]
print("\n",datas)
print("\n",precos)
datas = np.arange(1,88,1)

plt.plot(datas, precos[:,0])
plt.show()

Moscow = precos[:,0]
Kaliningrad = precos[:,1]
Petersburg = precos[:,2]
Krasnodar = precos[:,3]
Ekaterinburg = precos[:,4]

print("\n", Moscow)
print("\n", Kaliningrad)
print("\n", Petersburg)
print("\n", Krasnodar)
print("\n", Ekaterinburg)


