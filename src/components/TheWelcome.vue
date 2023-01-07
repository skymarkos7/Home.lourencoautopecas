<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import MotorIcon from "./icons/IconMotor.vue";
import BreakIcon from "./icons/BreakIcon.vue";
import OilIcon from "./icons/IconOil.vue";
import RadiatorIcon from "./icons/IconRadiator.vue";
import IconSuspension from "./icons/IconSuspension.vue";

</script>

<template>
  <WelcomeItem>
    <template #icon>
      <IconSuspension />
    </template>
    <template #heading> Suspensão</template>
    <p>
      amortecedor estourado, batedores arrebentados, buchas com folgas, coxins com defeito , terminais de direcao, pivos, articuladores , bieletas, suportes , Temos a soluçao...
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <!-- <img src="src/assets/paper.svg" width="30" height="30" alt=""> -->
      <BreakIcon />
    </template>
    <template #heading>Freios</template>
    <p>
      Trabalhando com pastilha de Freios, Lonas e sapatas, discos e tambores, cilindros e cilindros Mestre, burrinho de freio, Bomba de freio, oleo de freio, Cabos de Freios, flexiveis e canuites...
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <!-- <img src="src/assets/query.svg" height="30" width="30" alt="planejamento"> -->
      <MotorIcon />
    </template>
    <template #heading>Motor</template>

    <p>
      Retificacao de cabecotes, juntas do cabecotes e servicos em geral
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <!-- <img src="src/assets/group.svg" height="30" width="30" alt="assessoria"> -->
      <OilIcon />
    </template>
    <template #heading>Troca de Óleo</template>
    <p>
      contamos com uma diversidade de especificacoes de oleo lubrificantes, certamente o melhor pra seu carro, oleos Minerais, semissinteticos e sinteticos, 20w50, 15w40, 5w40, 5w30, 0w20, alem de oleo de Caixa de macha e de direcao hidraulica...
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <RadiatorIcon />
    </template>
    <template #heading>Arrefecimento</template>
    <p>
      agua desmineralizada, aditivos, limpeza no Sistema, Bomba de agua , cano de agua, cavalete de agua , espoletas entre outros

    </p>
  </WelcomeItem>

</template>
