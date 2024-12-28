# Programa para cálculo de IMC
def calcular_imc(peso, altura):
    imc = peso / (altura ** 2)
    return imc

def classificar_imc(imc):
    if imc < 18.5:
        return "Baixo peso"
    elif 18.5 <= imc < 25:
        return "Peso adequado"
    elif 25 <= imc < 30:
        return "Sobrepeso"
    elif 30 <= imc < 35:
        return "Obesidade grau I"
    elif 35 <= imc < 40:
        return "Obesidade grau II"
    else:
        return "Obesidade grau III"

# Entrada de dados
try:
    peso = float(input("Digite seu peso em kg: "))
    altura = float(input("Digite sua altura em metros: "))
    imc = calcular_imc(peso, altura)
    classificacao = classificar_imc(imc)
    print(f"Seu IMC é: {imc:.2f} ({classificacao})")
except ValueError:
    print("Por favor, insira valores válidos para peso e altura.")
