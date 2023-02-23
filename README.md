botaoCamisa = [[3, 1, 3], [6, 5, 5]]
camisaMes = [[100, 50], [50, 100], [50, 50]]
resultado = [[0, 0], [0, 0]]

for i in range(len(botaoCamisa)):
    for j in range(len(camisaMes[0])):
        for k in range(len(camisaMes)):
            resultado[i][j] += botaoCamisa[i][k] * camisaMes[k][j]

for linha in resultado:
    print(linha)
