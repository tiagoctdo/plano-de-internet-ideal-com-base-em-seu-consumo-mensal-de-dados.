# plano-de-internet-ideal-com-base-em-seu-consumo-mensal-de-dados.
Uma empresa de telecomunicações deseja criar uma solução algorítmica que ajude aos seus clientes a escolherem o plano de internet ideal 

def recomendar_plano(consumo_mensal):
    if consumo_mensal <= 10:
        return "Plano Essencial Fibra - 50Mbps"
    elif 1 <= consumo_mensal <= 20:
        return "Plano Prata Fibra - 100Mbps"
    elif consumo_mensal > 20:
        return "Plano Premium Fibra - 300Mbps"

# Solicita ao usuário que insira o consumo médio mensal de dados:
consumo = float(input())
# Chama a função recomendar_plano com o consumo inserido e imprime o plano recomendado:
print(recomendar_plano(consumo))
