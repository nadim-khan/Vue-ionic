<template>
<base-layout pageTitle="All Memories">
    
            <h2>These are my memories</h2>
            <ion-list>
                <ion-item router-link='/memories/1'>Trip to Lawasa</ion-item>
                <ion-item router-link='/memories/2'>Vacation on GOA</ion-item>
                <ion-item router-link='/memories/3'>Dinner at Kothrud</ion-item>
            </ion-list>
</base-layout>
</template>
<script lang="ts">

import {IonList, IonItem } from "@ionic/vue";
import BaseLayout from '@/components/base/BaseLayout.vue';

export default  {
    name:'MemoriesPage',
    components:{
        IonList,
        IonItem        
    }


    }
</script>>